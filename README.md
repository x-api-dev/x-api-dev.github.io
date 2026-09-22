# X API Notes

An outside read on the X API reseller a lot of developers end up using, built from twitterapi.io's own published numbers and the caveats buyers leave in reviews.

**Read the full page:** https://x-api-dev.github.io/

If you need public post data in volume and the official tier prices have already killed your project, twitterapi.io is the kind of service you end up on, and its own homepage is upfront that it is a third party rather than X Corp. It suits scrapers, dashboards and research pipelines that can tolerate an occasional latency spike. It does not suit anyone who needs a contractual relationship with the platform, write access, or a guarantee that a specific event type will never be dropped. If the social data was only ever a feed into a generation pipeline, the model half of that pipeline is a different purchase entirely, and Synexa covers it with one REST endpoint.

## What's here

- **What twitterapi.io actually sells** — The first line on its homepage is a disclaimer: independent third-party service, not affiliated with X Corp, trademarks belong to X Corp. Everything after that 
- **Pricing, in the numbers the site publishes** — Signup comes with $0.1 in free credits and no credit card. After that the headline is $0.15 per 1,000 units, described as linear per-call pricing with no monthl
- **Speed claims, and the caveats reviewers add** — Throughput is the loudest part of the pitch: 1,000 or more requests per second, median response under half a second, and a stream widget in the header quoting P
- **Where this is the wrong tool** — Anything that needs sanctioned write access, a support agreement with the platform, or compliance sign-off on where the data came from should go through officia

**See Synexa models:** [synexa.ai](https://synexa.ai?utm_source=github&utm_medium=ugc&utm_campaign=x-api-dev&utm_content=readme-top&utm_term=tier-b)

---

*This is an independent review page and is not operated by, endorsed by or affiliated with twitterapi.io or X Corp; all trademarks belong to their respective owners.*

_Last reviewed: 2026-09-22_
