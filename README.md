# Academic Homepage Template

A clean, responsive, single-page academic homepage designed for GitHub Pages.

## Included sections

- About Me
- Research Interests
- Selected Publications
- Honors and Awards
- Education
- Research Experience
- Contact Information
- Google Scholar, ORCID, and GitHub links
- CV download button

## File structure

```text
academic-homepage-template/
├── index.html
├── style.css
├── script.js
├── README.md
└── assets/
    ├── profile-placeholder.svg
    └── cv-placeholder.pdf
```

## Customize the website

Open `index.html` and replace the placeholder content:

- `Your Name`
- `Your Major`
- `Your University`
- Research interests
- Publication titles and links
- Award names and rankings
- Email address
- Google Scholar, ORCID, and GitHub URLs

Replace:

- `assets/profile-placeholder.svg` with your own photo, such as `profile.jpg`
- `assets/cv-placeholder.pdf` with your English CV

If you use a different image filename, also update the `src` value in `index.html`.

## Publish with GitHub Pages

1. Create a new public GitHub repository.
2. Upload all files in this folder to the repository root.
3. Open the repository's **Settings**.
4. Select **Pages** in the left sidebar.
5. Under **Build and deployment**, choose:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/ (root)**
6. Save the settings.
7. After deployment, your site will normally be available at:

```text
https://YOUR_GITHUB_USERNAME.github.io/REPOSITORY_NAME/
```

For a personal root homepage, name the repository:

```text
YOUR_GITHUB_USERNAME.github.io
```

Then the site address will be:

```text
https://YOUR_GITHUB_USERNAME.github.io/
```

## Publication entry example

```html
<article class="publication-card">
  <div class="publication-year">2026</div>
  <div>
    <h3>Your Paper Title</h3>
    <p class="authors">
      <strong>Your Name</strong>, Coauthor A, Coauthor B
    </p>
    <p class="venue">Conference or Journal, 2026</p>
    <p class="publication-description">
      A short summary of the paper's contribution.
    </p>
    <div class="publication-links">
      <a href="YOUR_PAPER_URL">Paper</a>
      <a href="YOUR_CODE_URL">Code</a>
    </div>
  </div>
</article>
```

## Optional improvements

- Add a custom domain.
- Add a favicon.
- Add Google Analytics or another privacy-friendly analytics service.
- Add a news section for recent updates.
- Add publication thumbnails.
- Add a bilingual English/Chinese version.
