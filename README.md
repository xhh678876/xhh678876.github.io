# Xie Haohui's Personal Homepage

[![GitHub Pages](https://img.shields.io/badge/GitHub-Pages-blue)](https://xhh678876.github.io)
[![License](https://img.shields.io/github/license/xhh678876/xhh678876.github.io)](LICENSE)

A modern, responsive bilingual academic homepage built with Jekyll.

🌐 **Live Site**: [https://xhh678876.github.io](https://xhh678876.github.io)

## Features

- **Bilingual Support**: Seamless switching between English (default) and Chinese
  - English: [https://xhh678876.github.io/](https://xhh678876.github.io/)
  - Chinese: [https://xhh678876.github.io/zh/](https://xhh678876.github.io/zh/)
- **Responsive Design**: Automatically adapts to different screen sizes
- **Clean & Modern**: Minimalist design suitable for academic homepages
- **SEO Optimized**: Search engine optimized for better discoverability

## Structure

```
├── _config.yml          # Site configuration
├── _data/
│   ├── navigation.yml   # Chinese navigation
│   └── navigation_en.yml # English navigation
├── _includes/           # Reusable components
├── _layouts/            # Page layouts
├── _pages/
│   ├── index.md        # English homepage (/)
│   └── about-zh.md     # Chinese homepage (/zh/)
├── images/             # Images and logos
└── assets/             # CSS and other assets
```

## Local Development

### Prerequisites
- Ruby 2.5+
- RubyGems
- GCC and Make

### Setup

1. Clone the repository:
```bash
git clone https://github.com/xhh678876/xhh678876.github.io.git
cd xhh678876.github.io
```

2. Install dependencies:
```bash
bundle install
```

3. Run the local server:
```bash
bash run_server.sh
# Or: bundle exec jekyll serve
```

4. Open [http://127.0.0.1:4000](http://127.0.0.1:4000) in your browser

## Deployment

The site is automatically deployed to GitHub Pages when you push to the `main` branch.

## Content Updates

### Personal Information
Edit `_config.yml` to update:
- Site title and description
- Author information (name, bio, location)
- Social media links

### Page Content
- **English version**: Edit `_pages/index.md`
- **Chinese version**: Edit `_pages/about-zh.md`

### Navigation
- **English navigation**: Edit `_data/navigation_en.yml`
- **Chinese navigation**: Edit `_data/navigation.yml`

## Acknowledgements

- Original template from [AcadHomepage](https://github.com/RayeRen/acad-homepage.github.io)
- Built with [Jekyll](https://jekyllrb.com/)
- Inspired by [minimal-mistakes](https://github.com/mmistakes/minimal-mistakes)

## License

This project is open source and available under the [MIT License](LICENSE).