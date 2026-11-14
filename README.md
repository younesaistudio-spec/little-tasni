# Little Tasni

**Crafted with love, made for little dreams.**

Little Tasni is a luxury kidswear **concept brand**: a one-page landing website showing the brand's story, a first collection of four pieces, a lifestyle moment and the brand colour palette. The feel is soft, calm and quietly luxurious, with ivory and blush tones, lots of white space, hairline details and elegant serif type.

**Live site:** LIVE_SITE_URL_HERE

## Concept brand

> Little Tasni is not a real store. It is a concept brand created as a portfolio project. There are no products for sale, no prices and no checkout. All product and lifestyle imagery is AI-generated.

Brand, visuals and website by Younes.

## Tools used

- **Claude Code**: website design and build (HTML/CSS)
- **Google Flow**: visual generation
- **Nano Banana**: image generation and editing
- **Midjourney**: product and lifestyle imagery

## What's inside

```
index.html     Single-page site
styles.css     All styles (brand tokens as CSS variables)
script.js      Small mobile-menu toggle
images/        Product and lifestyle imagery
```

Sections: Header · Hero · Our story · Collection · Lifestyle banner · Brand palette · Footer.

## Brand palette

| Name        | Hex       | Use                         |
|-------------|-----------|-----------------------------|
| Ivory       | `#F7F1E8` | Background                  |
| Linen       | `#FFFDF9` | Cards                       |
| Blush       | `#D9A5A0` | Accent, buttons             |
| Blush soft  | `#EFD9D4` | Tinted sections             |
| Sand        | `#C8A97E` | Thin rules, small details   |
| Cocoa       | `#4A3B33` | All text                    |
| Cocoa muted | `#76665C` | Secondary text              |
| Hairline    | `#E4D8C8` | Borders                     |

Typography: Cormorant Garamond (logo, headings) and Montserrat (body, labels, buttons).

## Quality notes

- Responsive layout, tested at 375px, 768px and 1440px
- Semantic HTML, descriptive alt text, visible focus styles, skip link
- Text contrast of at least 4.5:1 throughout
- Lazy-loaded images below the hero; meta description and Open Graph tags

## Run locally

No build step. Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server
```
