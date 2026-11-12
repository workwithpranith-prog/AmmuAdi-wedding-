# Ammu & Adi · Wedding Guide

A single-page guide for wedding guests: every event (Mehendi, Haldi, Sangeet, Muhurtham),
with venues, timings, dress codes, the invitations, and a search box that answers questions
like "haldi dress code", "where is sangeet" or "what's next?".

- `index.html` – the whole site (HTML, CSS and JS in one file, no build step)
- `images/` – the four invitation cards

## Updating the info
All the wedding details live in the `EVENTS` and `GENERAL` lists near the top of the
`<script>` in `index.html`. Edit them there and the event cards and search update together.
Add words to an event's `keywords` (or to `TOPICS`) to make search understand more phrasings.

## Putting it online (GitHub Pages)
Repository **Settings → Pages → Build and deployment → Deploy from a branch**, pick the branch
and `/ (root)`, save. The site appears at `https://<username>.github.io/<repo>/`.
Links like `.../?q=haldi` open with that search already filled in.
