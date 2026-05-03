# Hugo Lab Website Starter

This is a minimal Hugo starter for an academic research group website with pages for:

- Home
- News
- Research
- People
- Publications
- Contact

## Run locally

```bash
hugo server
```

Then open the local address Hugo prints in the terminal.

## Build static files

```bash
hugo
```

The generated site will appear in `public/`.

## Customize

- Edit `config.yaml` for lab name, tagline, affiliation, email, and menu.
- Edit `data/people.yaml` for group members.
- Edit `content/news/` markdown files for news posts.
- Edit `data/publications.yaml` for selected publications.
- Edit `content/` markdown files for each page.
- Edit `assets/css/style.css` to change appearance.

## Suggested next improvements

- Add a `positions/` page
- Import publications automatically from BibTeX or CSL JSON
- Add profile photos under `static/images/`
- Deploy with GitHub Pages or Netlify

## License

This repository is licensed under the MIT License. See `LICENSE` for details.

Third-party materials may be subject to separate copyrights.
