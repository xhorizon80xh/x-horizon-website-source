# X HORIZON website source

Organized source archive for the X HORIZON website. The main page and templates are embedded in Odoo Online, so this repository is a versioned source archive and is not a deployable copy of the Odoo database.

## Layout

- `pages/community-guidelines/index.html` — current Community Guidelines page source copied from Odoo's embedded editor on 2026-10-24.
- `source/homepage/` — local homepage source snapshots.
- `source/custom-pages/` — local custom page and category source snapshots, preserving their folder layout.
- `source/system-library/` — local shared CSS, JavaScript, and template source snapshots.
- `source/public-contributions/` — code-only public contribution sources, when present.

Original snapshot filenames and extensions are preserved. Some Odoo editor exports are stored as `.txt` files because that is how they were saved locally. Their contents are retained verbatim.

## Scope

Only text-based website source files (`.html`, `.htm`, `.txt`, `.js`, `.css`, `.json`, and `.xml`) are included. Local media libraries, PDFs, office documents, and audit notes are excluded. The source files are snapshots from the workspace; except for the Community Guidelines page, they have not been re-exported from the live Odoo editor as part of this repository preparation.

Review any configuration values before reusing these source snapshots. Do not commit credentials or private keys.
