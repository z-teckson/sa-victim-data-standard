# Changelog

All notable changes to the South African Victim Data Standard (SA‑VDS) will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [v1.0] – 2025‑12‑30

### Added
- Initial release of the standardized data collection template.
- Sections for:
  - Victim demographics (anonymized)
  - Trafficking information (type, recruitment, transport, duration)
  - Health & psychosocial indicators
  - Intervention details (services, legal outcomes)
  - Follow‑up & long‑term support

### Updated
- **Based on stakeholder feedback** (Issues #1, #2, #3):
  - Added **travel document status** and **visa type** fields (migration/border control needs).
  - Added **case officer contact details** and **evidence collection log reference** (law enforcement needs).
  - Added **mental health screening tool used** and **medication prescribed** fields (healthcare provider needs).

### Notes
- All new fields are optional and can be marked “N/A” where not applicable.
- The template is designed to be POPIA‑compliant; personally identifiable information (PII) must be stored separately and linked via the unique anonymized ID.
- This version represents the consensus of the Inter‑Agency Task Team on Human Trafficking after a structured feedback process.

### Contributors
- South African Police Service (SAPS) & Hawks
- National Prosecuting Authority (NPA)
- Department of Social Development
- Department of Health
- Department of Home Affairs
- Civil society organisations (NGOs)
- Academic and research institutions

---

*For a detailed record of changes, see the commit history and pull requests in this repository.*