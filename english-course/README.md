# ቋንቋ to Career — Full Site Package

## Files
- **index.html** → Homepage (matches the live site, Enroll buttons wired to /login)
- **login.html** → Student registration + sign-in
- **admin.html** → Internal admin dashboard
- **_redirects** → Netlify config so /login and /admin work without .html
- **README.md** → This file

## Deploy (Drag & Drop)
1. Unzip this folder somewhere on your computer
2. Open https://app.netlify.com/sites/englishcourse3/deploys
3. Drag the WHOLE FOLDER (not the zip) into the drop zone at the bottom
4. Wait 30 seconds — site goes live

## URLs After Deploy
- https://englishcourse3.netlify.app/        → Homepage
- https://englishcourse3.netlify.app/login   → Student register/login
- https://englishcourse3.netlify.app/admin   → Admin dashboard

## Admin Login
- Username: `admin`
- Password: `aylabs2026`

(Change these inside admin.html — top of the <script> section — to match your real bakery credentials.)

## First-Time Admin Setup
On first visit to /admin, log in then paste:
1. Netlify Personal Access Token → app.netlify.com → User settings → Applications
2. Site ID → Site settings → General → Site information

Saved locally in your browser only.

## Form Detection
On first deploy, submit ONE test registration so Netlify auto-detects the form.
After that, all submissions show up in:
- app.netlify.com → Forms (Netlify's native view)
- Your /admin dashboard (the prettier view)
- Your email (auto-notifications)
