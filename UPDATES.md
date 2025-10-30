# UPDATES - LRING Homepage

## Version History

### lring_homepage_v8.html - 24 Octobre 2025
**Focus: Harmonised Header & Hero Alignment**

#### Previewing this Version
- **Production URL after merge:** `https://yazzou.github.io/lringstatic/lring_homepage_v8.html`
- **Branch preview (before merge):** `https://rawcdn.githack.com/yazzou/lringstatic/work/lring_homepage_v8.html`

> GitHub Pages only publishes files from the default branch. Use the branch preview link (or run `python3 -m http.server` locally) if you need to review the page before the pull request is merged.

#### Key Improvements:
1. **Introduced a shared `.layout-container`** to align the header grid, optional top bar, and hero slider text on a common horizontal rhythm.
2. **Softened the hero headline typography** by reducing weight, size, and letter-spacing so it transitions more naturally from the main navigation.
3. **Updated responsive padding** to keep the shared container proportions consistent on tablets and phones.

#### Technical Changes:
- Added the reusable `.layout-container` helper and applied it to header and slider content blocks.
- Adjusted `.slide-title` styling and overlay padding for cohesive hierarchy.
- Synced breakpoint rules so container padding scales at `1200px` and `768px` widths.

### lring_homepage_v4.html - 24 Octobre 2025
**Focus: Dual-Level Header with Contact & Social Strip**

#### Key Improvements:
1. **Introduced top utility bar** combining first-level navigation links, square social icons, and contact details for immediate access.
2. **Rebuilt primary header grid** so left/right navigation clusters hug the centered logo, tightening the luxury layout.
3. **Refined responsive behavior** with adaptive spacing and stacked contact details to keep the header readable on smaller viewports.

#### Technical Changes:
- Added `.site-header`, `.top-bar`, and supporting classes to manage the new two-tier header structure.
- Converted `.header-container` to a three-column CSS grid to better control navigation positioning around the logo.
- Updated mobile breakpoint (`max-width: 768px`) to reorganize top-bar content and maintain burger-first navigation on phones.

### lring_homepage_v3.html - 24 Octobre 2025
**Focus: Sophisticated Header with Centered Logo & Improved Menu**

#### Key Improvements:
1. **Enhanced Hero Section - Text Readability:**
   - **Added subtitle layer** between image and text for improved readability
   - **Implemented gradient overlay** from 95% to 30% opacity white
   - **Enhanced text contrast** against background images

2. **Hero Title Enhancement:**
   - **Removed padding from title** (margin: 0) for cleaner, more impactful presentation
   - **Increased title size** from 48px to 56px for luxury emphasis
   - **Enhanced letter spacing** from 2px to 3px for better visual hierarchy
   - **Added text shadow** for improved readability over images
   - **Improved line height** to 1.1 for tighter luxury feel

3. **Overlay Improvements:**
   - **Multi-layer gradient background** for smooth text readability transition
   - **Maintained luxury aesthetic** while enhancing functionality
   - **Preserved responsive design** with mobile-optimized title sizing

#### Technical Changes:
- Modified `.slide-overlay` CSS with gradient background
- Updated `.slide-title` CSS: removed margin, increased size and spacing
- Enhanced responsive breakpoints for mobile compatibility
- Maintained black and white color scheme requirement
- Preserved luxury typography and spacing standards

### lring_homepage_v1.html - Initial Implementation
**Base Features:**
- Black and white luxury design with Oswald typography
- Full-width hero slider with project showcases
- Competences section (Structure, Enveloppe, R&D, ACV, BIM)
- Projects section with featured and iconic projects
- Responsive burger menu appearing on scroll
- Footer with navigation and contact information

---

## Design Philosophy
- **Strict black and white color scheme** (no gradients or colors)
- **Luxury minimalism** with emphasis on typography and spacing
- **Responsive design** maintaining luxury feel across devices
- **High-end architectural bureau** positioning
- **Oswald font family** for professional, technical appearance
