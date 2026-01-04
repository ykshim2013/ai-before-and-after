# Reveal.js Presentation for GitHub Pages

## Quick Start

### Local Preview
Open `index.html` in your browser, or use a local server:
```bash
# Python 3
python -m http.server 8000

# Then open http://localhost:8000
```

### Deploy to GitHub Pages
1. Create a new GitHub repository
2. Push this folder to the repository
3. Go to **Settings → Pages**
4. Under "Source", select **main branch** and **/ (root)**
5. Your presentation will be live at `https://yourusername.github.io/repo-name`

## Keyboard Controls

| Key | Action |
|-----|--------|
| `→` or `Space` | Next slide |
| `←` | Previous slide |
| `↓` | Next vertical slide |
| `↑` | Previous vertical slide |
| `Esc` or `O` | Overview mode |
| `S` | Speaker notes (open in new window) |
| `F` | Fullscreen |
| `B` or `.` | Pause/blackout |

## Customization

### Change Theme
Edit line 9 in `index.html`:
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/reveal.js@5.1.0/dist/theme/black.css">
```

Available themes: `black`, `white`, `league`, `beige`, `sky`, `night`, `serif`, `simple`, `solarized`, `blood`, `moon`, `dracula`

### Add Speaker Notes
```html
<section>
    <h2>Slide Title</h2>
    <p>Visible content</p>
    <aside class="notes">
        Speaker notes go here (press S to view)
    </aside>
</section>
```

### Fragment Animations
```html
<ul>
    <li class="fragment">Appears first</li>
    <li class="fragment fade-up">Fades up second</li>
    <li class="fragment highlight-red">Highlights third</li>
</ul>
```

### Background Options
```html
<!-- Solid color -->
<section data-background-color="#4a86e8">

<!-- Image -->
<section data-background-image="image.jpg" data-background-size="cover">

<!-- Gradient -->
<section data-background-gradient="linear-gradient(to bottom, #283048, #859398)">
```

## Resources
- [Reveal.js Documentation](https://revealjs.com/)
- [Markdown Plugin](https://revealjs.com/markdown/)
- [Themes Gallery](https://revealjs.com/themes/)
