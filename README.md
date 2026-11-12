# 12 INCHES — Website V1

Responsive bilingual (English/Hindi) static website for 12 INCHES, Bareilly, Uttar Pradesh, India.

## Business details
- Studio: Bareilly, Uttar Pradesh, India
- Contact: Eng. Ahsan Aziz
- Phone / WhatsApp: +91 84770 30820
- WhatsApp link: https://wa.me/918477030820

## Deploy to GitHub + Cloudflare Pages

### 1. Create a GitHub repository
Create a new repository, for example `12-inches-website`. Upload the contents of this folder (not the enclosing folder) to the repository root. The root must contain `index.html` and the `assets/` directory.

### 2. Connect Cloudflare Pages
1. Sign in to Cloudflare.
2. Open **Workers & Pages** → **Create** → **Pages** → **Connect to Git**.
3. Select the GitHub repository.
4. Framework preset: **None** (or **Static HTML** if shown).
5. Build command: leave blank.
6. Build output directory: `/` (repository root).
7. Save and deploy.

Cloudflare Pages will publish the site and provide a `*.pages.dev` URL. Subsequent pushes to the connected production branch will trigger deployments automatically.

### 3. Optional custom domain
In the Pages project, open **Custom domains** → **Set up a custom domain**, enter the domain you own, and follow Cloudflare's DNS instructions.

## Local preview
Open `index.html` in a browser. For a local server, run:
```bash
python -m http.server 8000
```
Then visit `http://localhost:8000`.

## Important content notes
- The website is a static frontend prototype; no CMS, server-side enquiry storage, or admin panel is included.
- WhatsApp enquiry uses the supplied business number.
- Portfolio images are illustrative architectural/interior reference photography, not verified 12 INCHES completed projects. Replace them with authorised studio project photos before presenting them as completed work.
- Check all text, service claims, phone details, and image rights before public launch.
