# Job Dashboard

Yash's validated job-hunt dashboard. Snapshot: **September 29, 2026** — 29 junior-to-mid
roles across AI/ML, Forward Deployed, SRE, Backend, and Data Engineering.

## View it

Open `index.html` in a browser, or enable GitHub Pages on this repo
(Settings → Pages → Deploy from branch → main) for a live link.

## Files

- `index.html` — the dashboard: instant search, filters (role family, work mode,
  employment type), summary counts, CSV download, direct job links.
- `jobs.json` — the same 29 jobs as machine-readable data
  (id, title, company, location, pay, type, experience, source, posted,
  apply_by, url, work_auth).
- The companion workbook `Validated Handshake Jobs.xlsx` lives alongside the
  dashboard export in the workspace; the canonical data here is `jobs.json`.

## Verification notes

- Handshake's 10 postings were live-browser validated on 2026-09-29.
- The 19 US-wide sweep postings were checked via direct HTTP/full-body fetches;
  Built In posted dates on those rows are unconfirmed ("Date unconfirmed").
- SpaceX backend role: ITAR/US-person requirement noted in the data.
- No role here requires 5+ years, a senior title, or federal clearance.
