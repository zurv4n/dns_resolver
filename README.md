# dns_resolver
checks cloudflare dns entries and updates if necessary

## Requirements

This is made to work with Cloudflare API. If Cloudflare is not managing the DNS for your domains, this program will not be successful.

## Install

Just copy the file ipcheck somewhere on your server

## Usage

You are able run this manually or set to run on a schedule. There are limits in place at both ipify and cloudflare for number of checks so ensure to be cognizant of those. Be sure to edit the file to enter values (domainID and bearer token) that match your domains and your Cloudflare API bearer token. It takes care of the rest and produces a log out put when run. It will work any number of domains by extending the list on line 5.

this will be removed