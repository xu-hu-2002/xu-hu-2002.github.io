# Xu Hu — personal homepage

A minimal academic homepage (layout inspired by jykoh.com). Plain HTML/CSS, no build step.

## Files
- `index.html` — home (intro, photo, news)
- `publications.html` — publication list
- `styles.css` — all styling
- `profile.jpg` — profile photo

Photo and GitHub link (`https://github.com/xu-hu-2002`) are already set — nothing to edit before publishing.

## Deploy on GitHub Pages
1. Create a repo named `xu-hu-2002.github.io` (this makes it your main GitHub homepage at `https://xu-hu-2002.github.io`).
2. Put these files at the repo root.
3. Push:
   ```
   git init
   git add .
   git commit -m "personal homepage"
   git branch -M main
   git remote add origin https://github.com/xu-hu-2002/xu-hu-2002.github.io.git
   git push -u origin main
   ```
4. In the repo: **Settings → Pages → Source: Deploy from a branch → main / root**. Your site goes live at `https://xu-hu-2002.github.io` within a minute or two.

To preview locally: `python3 -m http.server` in this folder, then open `http://localhost:8000`.
