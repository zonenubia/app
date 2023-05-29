<p align="center"><img src="https://zonenubia.github.io/favicon.png" height="128"></p>
<h1 align="center">Awdev Register</h1>


<p align="center">Awdev Free subdomains for personal sites, open-source projects, and more.</p>
<p align="center">Want to find services similar to this? Take a look on <a href="https://www.awdev.my.id/#/?id=domains">AWDEV</a>.</p>

## Notice
While we do support NS records we now only now accept NS records for valid reasons.

## Donate
If you like this service and want us to continue running it, please consider donating!

[PayPal](https://www.awdev.my.id)

### Discord Server
Make sure to join our Discord server:
https://discord.gg

## Domains

| Available Domains |
|:-:|
| [`*.awdev.my.id`](https://awdev.my.id) |
| [`*.app.awdev.my.id`](https://app.awdev.my.id) |
| [`*.go.awdev.my.id`](https://go.awdev.my.id) |
| 

> Wildcard domains (like `*.example.awdev.my.id`) are supported too, but the reason for their registration should be very clear and described in detail.

[badge-cf]:https://shields.io/badge/%20-cloudflare-blue?logo=cloudflare&style=plastic?cacheSeconds=3600
[badge-dnssec]:https://shields.io/badge/%20-DNSSEC-blue?logo=moleculer&logoColor=white&style=plastic?cacheSeconds=3600
[badge-ssl]:https://shields.io/badge/SSL-Required-blue?style=plastic?cacheSeconds=3600

### Unsupported Services
We currently do not support Cloudflare (for NS), Netlify (for website) or Vercel (for websites).

This will hopefully be fixed soon.


## Register a Domain
1. **Star** and **[Fork](https://github.com/zonenubia/register/fork)** this repository.
2. Add a new file called `example.domain.json` in the `/domains` folder to register `example` subdomain.
3. Edit the file (below is just an **example**, provide a **valid** JSON file with your needs, the format is very strict.

```json
{
    "description": "Project Description",

    "domain": "awdev.my.id",
    "subdomain": "example",

    "owner": {
        "repo": "https://github.com/username/repo",
        "email": "hello@example.com"
    },

    "record": {
        "A": ["1.1.1.1", "1.0.0.1"],
        "AAAA": ["::1", "::2"],
        "CNAME": "example.com",
        "MX": ["mx1.example.com", "mx2.example.com"],
        "NS": ["ns1.example.com", "ns2.example.com"],
        "TXT": ["example_verification=1234567890"]
    },

    "proxied": false
}
```

4. Your pull request will be reviewed and merged. Please don't ignore the pull request checklist. If you ignore the checklist, your pull request will be ignored too. _Make sure to keep an eye on it in case we need you to make any changes!_
5. After the pull request is merged, please allow up to 24 hours for the changes to propagate _(usually, it takes 5..15 minutes)_
6. Enjoy your new domain!

*Domains used for illegal purposes will be removed and permanently banned. Please, provide a clear description of your resource in the pull request.*

### License
This project is under a [MIT License](https://github.com/zonenubia/app/register/blob/main/LICENSE).
