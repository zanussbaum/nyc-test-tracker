# NYC COVID-19 Testing Wait Times PDF Scraper

![request to create a scraper for nyc testing times](https://i.ibb.co/HDg0YSQ/image.png)

Challenge accepted!

This repo will automatically run the scraper every 15 minutes with a cronjob set up through GitHub Actions. Thanks to this [wonderful blog post](https://jasonet.co/posts/scheduled-actions/) from Jason Etcovitch that had most of the action automation setup I pulled from for the workflow.

The csv filenames are structured as `{two-hour time window}-{scrape timestamp}.csv`.
