# Supplier Catalog Portal

Shared catalog workspace for the Meridian Outfitters sourcing desk and its wholesale partners.

## Layout

- `catalog/index/` — supplier search indexes, one page per buying category
- `catalog/items/` — live item records, one markdown file per SKU; every record declares its own canonical URL
- `catalog/legacy/` — archived crawl pages retained so old search links keep working
- `catalog/brands/` — brand and collection landing pages
- `catalog/qa/` — merchandising QA artifacts, including the review queue
- `catalog/curation/` — published buying shortlists

## Notes

- The live item record is the system of record for title, seller, price and availability.
- Search indexes are rebuilt from periodic crawls and can lag behind record edits.
- Prices are quoted in the currency shown on the live record.
