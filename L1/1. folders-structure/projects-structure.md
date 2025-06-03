# 🧱 Level 1: Beginner – Web Project Structure

Welcome! This guide introduces you to a simple and well-organised folder structure for your first web project.  
No frameworks, no complex tools – just **HTML**, **CSS**, images, and good habits.

---

## 📁 Recommended Folder Structure

project-name/

├── index.html ← Main HTML file (home page)
├── css/
│ └── style.css ← All your styles (colours, layout, etc.)
├── assets/
│ ├── imgs/ ← Store images (logos, backgrounds)
│ └── fonts/ ← Optional: custom fonts
└── README.md ← Project notes or setup guide


---

## 🔍 Folder Purpose

| **File or Folder**        | **Purpose**                                                      |
|---------------------------|------------------------------------------------------------------|
| **_`index.html`_**        | Your main web page. The browser opens this file first.           |
| **_`css/style.css`_**     | All your styling rules – colours, fonts, spacing, layout, etc.   |
| **_`assets/imgs/`_**      | Store images used in your project (e.g. logo, background).        |
| **_`assets/fonts/`_**     | Store custom fonts (optional, for advanced styling).              |
| **_`README.md`_**         | Notes, instructions, or your personal learning log.               |

---

## 💡 Tips & Good Practices

- ✅ **Use lowercase and dashes** in filenames  
  Example: `contact-page.html` **not** `Contact Page.html`

- ✅ **Always link your CSS file in the `<head>`**  
  Use: `<link rel="stylesheet" href="css/style.css">`

- ✅ **Use relative paths** for images and files  
  Example: `<img src="assets/imgs/logo.png" alt="Logo">`

- ✅ **Keep your code indented and readable**  
  Use 2 or 4 spaces – <u>**be consistent**</u> across all files

- ✅ **Use semantic HTML tags**  
  Prefer `<header>`, `<main>`, `<section>`, `<footer>` over just `<div>`

- ✅ **Organise styles logically**  
  Group related CSS rules together (e.g., typography, layout, colours)

- ✅ **Comment your CSS**  
  Example: `/* Navigation styles */`

- ✅ **Avoid inline styles in HTML**  
  Keep all your styling in `style.css` for clean separation

- ✅ **Test in multiple browsers**  
  Make sure your site looks good in both Chrome and Firefox

- ✅ **Keep image file sizes small**  
  Use `.jpg` for photos and `.png` or `.svg` for graphics or logos