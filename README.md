# Kink Jars — Expanded

Fork of [LockedTony/kink-jars](https://github.com/LockedTony/kink-jars), retaining the original canvas jar artwork and colour picker.

## Features

- 350 built-in, non-graphic labels for adult interests, dynamics, equipment and fantasies.
- Search and category filters, with a paginated questionnaire.
- Add and remove custom jars without editing code; duplicate labels are rejected.
- Rate jars from 1 to 5. Tap the selected rating again to return to zero.
- Preview and PNG export omit every zero-valued jar and compact the remaining grid.
- Name, colour, answers and custom jars persist in browser localStorage. Answers are not uploaded.
- Long exports scale down to keep image height within 16,000 pixels.

## Catalogue references

Reference lists consulted October 9, 2026: [BDSM Checklist](https://bdsmchecklist.com/activities), [KinkCodex](https://knowyourkinkcode.com/kink-codex/glossary/), [Wikipedia BDSM glossary](https://en.wikipedia.org/wiki/Glossary_of_BDSM), and [FetLife Kinktionary](https://fetlife.com/kinktionary).

This is an extensible catalogue, not a claim to enumerate every kink. Categories and role variants are editorial organization; the reference lists do not individually verify every variant. Labels describe consensual adult interests and fantasies, not instructions or an agreement to participate.

## Hosting

Enable GitHub Pages from `main` and `/ (root)`. The app is the standalone `index.html`; no build or server is required. Fonts load from Google Fonts, with system fallbacks.

## Validation

JavaScript syntax checked. Node checks passed for catalogue uniqueness, empty-poster handling, nonzero-only compact rendering, export dimensions and saved custom-jar restoration. Browser interaction QA is separate.
