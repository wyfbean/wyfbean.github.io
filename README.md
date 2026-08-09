# Yifan Wu — Personal Profile

The source for [wyfbean.github.io](https://wyfbean.github.io), a one-page research and engineering portfolio built with Hexo.

## Local development

```bash
npm install
npm run serve
```

Then open `http://localhost:4000`.

## Production build

```bash
npm ci
npm run build
```

The generated site is written to `public/`.

## Deployment

Every push to `main` runs the GitHub Actions workflow in `.github/workflows/pages.yml`. The workflow builds the Hexo site and deploys the generated `public/` directory to GitHub Pages.

For the first deployment, open **Settings → Pages** in the repository and select **GitHub Actions** as the publishing source.

## Content updates

Profile content is stored in `source/_data/profile.yml`. The page template and styles live in the custom `themes/profile` theme.

## License

Code is available under the MIT License. Personal profile content remains © Yifan Wu.
