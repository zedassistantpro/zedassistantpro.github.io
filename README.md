# ZED Bronze Assistant

A Chrome side panel that drafts assessment remarks for assessors carrying out
**MSME ZED Bronze** certification assessments on the ZED portal.

It asks what you can see in the evidence in front of you and composes the
remark wording from your answers. It does not assess anything, it does not
decide whether evidence is acceptable, and **it is not affiliated with the
Quality Council of India or the Ministry of MSME**.

**[Read more at zedassistantpro.github.io](https://zedassistantpro.github.io/)**

## Two builds

| | Free | Pro |
|---|---|---|
| Requirements covered | Two sections in full — Site Exterior Photos, and Product Photographs & Description | All seventeen |
| Suggested remark wording | Yes | Yes |
| Final submission wording | No | Yes |
| Location checks | No | Yes |
| Auto-fill | No — it never presses Submit | Only the requirements you tick, each marked in red on the page |
| Licence | None needed | One named assessor, ₹500 a month |

The free build is not a trial. It covers its two sections completely and goes
on doing so.

## Privacy, briefly

No assessment information leaves your browser — not the unit, not the remarks,
not the evidence, not the verdicts. The free build sends nothing at all. Pro
sends only its licence key and the assessor ID shown as signed in, about twice
a day, to check the licence is valid. The portal password is never read, stored
or transmitted. [Full policy](https://zedassistantpro.github.io/privacy.html).

## This repository

This repo holds only the three public pages — the site you are reading about.
The extension source is kept separately.

- [`index.html`](index.html) — what it does, Free and Pro, the common questions
- [`disclaimer.html`](disclaimer.html) — scope: no affiliation, dependence on
  the portal, where the verdict rests
- [`privacy.html`](privacy.html) — the privacy policy the Chrome Web Store
  listing points at
- [`uninstall.html`](uninstall.html) — shown by Chrome after an uninstall; not
  indexed

## Contact

[Support, suggestions and licence requests](https://docs.google.com/forms/d/e/1FAIpQLSc3BiIv0qyrvI40dGZ_7E3fNNBmGfmUH_vlH2tqha3qjHID6w/viewform)
· [zedassistantpro@gmail.com](mailto:zedassistantpro@gmail.com)
