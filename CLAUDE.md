# Moody Hair — Website Project

## Project Overview
One-page, high-converting website for a professional hair stylist. Mobile-first, luxury aesthetic. Designed to showcase work and drive bookings.

## Tech Stack
- HTML5, CSS3, vanilla JavaScript
- No frameworks — keep it lightweight and fast
- Single `index.html` with embedded CSS/JS (or linked files if modular)

## Design System (MATCH THE PRICE LIST EXACTLY)

### Color Palette
| Role | Color | Hex |
|------|-------|-----|
| Background | Soft ivory / cream | `#FAF6F1` |
| Background alt | Light marble cream | `#F5EDE4` |
| Accent primary | Bronze / caramel gold | `#B8866B` |
| Accent secondary | Warm gold-brown | `#C4956A` |
| Accent highlight | Soft gold | `#D4A574` |
| Text primary | Soft dark brown | `#5C4033` |
| Text secondary | Warm medium brown | `#8B7355` |
| Dividers / borders | Light tan | `#E8D5C4` |
| White overlay | Soft white | `#FFFDF9` |

### Typography
- Headings: Elegant serif (Playfair Display or similar)
- Body: Clean sans-serif (Lato, Montserrat, or similar)
- Price list headings: Uppercase, spaced tracking, serif
- Do NOT use harsh black (#000) for any text

### Visual Rules
- Subtle marble/watercolor textures for backgrounds (matching price list)
- Gold fleck/splatter accents sparingly
- Smooth, subtle animations only — no flashy effects
- Light shadows, soft borders
- Feminine, premium salon feel throughout
- NO bright colors, neon, harsh blacks, or dark UI

## Page Structure (Single Page — Scroll Sections)

### 1. Hero Section
- Full-screen with looping video background (use the .mp4 files)
- Overlay: headline + two CTA buttons ("Book Now" / "View Work")
- Smooth scroll to respective sections

### 2. Portfolio Section
- Grid or carousel of hair work images/videos
- Lightbox on click
- Images: image.png, image2.png, image3.png
- Videos: the two SnapInsta .mp4 files

### 3. Services & Pricing Section
- Pull directly from price list:
  - **Quick Weaves:** Basic Quick-Weave $100, Blunt Cut Bob $120, Mid Half Up Half Down $120+, Flip Over $110, No Part Ponytail $85, Bun Hairstyles $100+
  - **Knotless Braids:** Large $100, Med $150, Small $190, Stitch Braids + Quick Weave $145+
  - **Extras:** Curls $15, Crimps $25, Wash + Blow Dry $15, Layers $10
  - **$10 deposit required to book**

### 4. About Section
- Short trust-building bio (placeholder text until client provides)
- Professional tone, focus on experience and results

### 5. Booking Section
- Clean form: Name, Phone, Service (dropdown from price list), Date, Time
- Mobile-friendly, minimal fields
- $10 deposit note displayed prominently

### 6. CTA / Footer
- Final push to book
- Contact info / social links placeholder

## Development Rules
- **DO NOT rebuild the entire site when making changes — only edit the specific section requested**
- Keep code clean, modular, and well-commented by section
- Optimize all images for web (compress where possible)
- Mobile-first responsive design
- Smooth scroll behavior throughout
- Reusable CSS classes for consistency
- Fast load times — minimize bloat

## File References
- `price list.jpg` — the design reference for colors and typography feel
- `image.png`, `image2.png`, `image3.png` — portfolio photos
- `SnapInsta.to_AQMf...mp4` — portfolio/hero video 1
- `SnapInsta.to_AQPW...mp4` — portfolio/hero video 2

## Workflow
- Ask before making assumptions about content, names, or branding
- Names and prices can be updated later — use what's on the price list for now
- Every design decision should optimize for: user experience, visual appeal, conversion rate
