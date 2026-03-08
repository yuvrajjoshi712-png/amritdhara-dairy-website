# Amritdhara DugdhaVatika Website

This is now a **multi-page static website** with:
- `index.html` (Redirects to Language page first)
- `home.html` (Home)
- `about.html` (About Us / Story)
- `products.html` (Products)
- `contact.html` (Contact)
- `language.html` (Language selection page)
- shared `styles.css`
- local placeholder images inside `images/`

## Why images were not visible earlier
Your previous code used text placeholders like `download.jpeg` inside a `<div>` instead of actual `<img>` tags, or the image files were not present in the expected path.

Now images are visible by default because real image files are included in `images/`:
- `images/hero-farm.svg`
- `images/farm-1.svg`
- `images/farm-2.svg`
- `images/farm-3.svg`

## How to use your real farm photos
1. Put your real photos into the `images/` folder.
2. Either:
   - keep the same names (`farm-1.svg`, etc.) after converting/replacing, **or**
   - change file names in HTML `src` attributes.
3. Recommended formats: `.jpg`, `.jpeg`, `.png`, `.webp`.
4. Example:
   ```html
   <img class="photo" src="images/my-real-farm-photo.jpg" alt="Farm photo" />
   ```

## Run locally
### Option 1: VS Code Live Server
- Open folder in VS Code
- Right-click `index.html` → **Open with Live Server**

### Option 2: Python server
```bash
python3 -m http.server 5500
```
Then open: `http://127.0.0.1:5500/index.html` (it will open language page first)

## Contact placeholders already configured
- Phone: `+91 9584051815`
- WhatsApp link: `https://wa.me/919584051815`
- Map: `https://maps.app.goo.gl/zELPRGbYC4CQBDwD8`
