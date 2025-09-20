# Resume Template

This repository provides a minimal Jekyll resume site with all content fields cleared out so you can start fresh. Populate the YAML data files under `_data/` and the profile information in `_config.yml` to publish your own resume.

## Getting started

### Prerequisites

- [Ruby](https://www.ruby-lang.org/en/downloads/) 3.1 or newer
- [Bundler](https://bundler.io/)

### Install dependencies

```bash
bundle install
```

### Run locally

```bash
bundle exec jekyll serve
```

Open [http://localhost:4000](http://localhost:4000) to preview the site. Changes to templates or data files will hot-reload while the server is running.

## Updating content

- `_config.yml` holds global profile information such as the headline, contact details, section toggles, and social links.
- Files inside `_data/` store the structured resume content. Each file contains comments with the expected structure for the entries.
- `_layouts/resume.html` controls the overall page structure if additional sections are required.

## Deployment

GitHub Actions automatically builds and publishes the site to GitHub Pages whenever changes are pushed to the `main` branch. The workflow lives in `.github/workflows/deploy.yml` and uses the official `actions/jekyll-build-pages` action, so no manual deployment steps are required.

## License

This project is released under the [MIT License](LICENSE).
