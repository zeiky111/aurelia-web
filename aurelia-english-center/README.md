# Aurelia English Center - Modern Website

A stunning, professional website for Aurelia English Center built with modern web technologies and best practices in UI/UX design.

## 🌟 Features

### Design Excellence
- **Premium Color Scheme**: Navy blue (#1a3a52, #2c5aa0) and Gold (#d4a574) based on company branding
- **Modern Layout**: Clean, spacious design with proper typography hierarchy
- **Professional Visual Elements**: Gradients, shadows, and animations for depth
- **Responsive Design**: Fully optimized for desktop, tablet, and mobile devices

### Pages Included
1. **Home Page** - Hero section, highlights, features, videos, and CTA
2. **About Page** - Company story, mission/vision, values, and statistics
3. **Services Page** - Course programs, learning formats, special programs, and pricing
4. **Contact Page** - Contact information, inquiry form, map section, and FAQ

### Key Features
✓ Smooth animations and transitions
✓ Interactive navigation with mobile hamburger menu
✓ Contact form with validation
✓ Video embeddings from YouTube
✓ Mobile-responsive grid layouts
✓ Accessibility-friendly design
✓ Fast loading and optimized performance
✓ Social media integration
✓ Scroll-to-top button
✓ Professional typography with Google Fonts

## 📁 Project Structure

```
aurelia-english-center/
├── index.html              # Home page
├── about.html              # About us page
├── services.html           # Services & programs page
├── contact.html            # Contact page
├── css/
│   └── styles.css         # Main stylesheet
├── js/
│   └── script.js          # JavaScript for interactivity
├── images/                # Placeholder for images
└── README.md              # This file
```

## 🎨 Color Palette

- **Primary Dark**: #1a3a52 (Navigation, headings)
- **Primary Blue**: #2c5aa0 (Links, highlights)
- **Primary Gold**: #d4a574 (Accents, decorative)
- **Light Background**: #f8f9fa (Sections)
- **White**: #ffffff (Main background)
- **Dark Text**: #333333 (Body text)
- **Light Text**: #666666 (Secondary text)

## 🔧 How to Use

1. **Extract Files**: Unzip the project to your desired location
2. **Open in Browser**: Open `index.html` with your web browser
3. **Alternative**: Use a local server:
   ```bash
   python -m http.server 8000
   # OR
   npx http-server
   ```
4. **Access**: Navigate to `http://localhost:8000` in your browser

## 📝 Customization Guide

### Update Company Information
Open each HTML file and update:
- Phone numbers in contact section
- Email addresses
- Location details
- Social media links

### Change Colors
Edit CSS variables in `css/styles.css`:
```css
:root {
    --primary-dark: #1a3a52;
    --primary-blue: #2c5aa0;
    --primary-gold: #d4a574;
    /* Update these values */
}
```

### Add Images
Place image files in the `images/` folder and update:
- Replace placeholder divs with actual images
- Update image paths in HTML

### Embed Your Videos
In `index.html` and `services.html`, replace YouTube video IDs:
```html
<iframe src="https://www.youtube.com/embed/YOUR_VIDEO_ID?rel=0"></iframe>
```

### Update Pricing
Edit pricing cards in `services.html` section:
```html
<p class="price">₱5,000<span>/month</span></p>
```

### Modify Navigation Links
Update navigation URLs in the navbar for both mobile and desktop views.

## 🚀 Deployment

### Netlify (Recommended - Free)
1. Sign up at [netlify.com](https://netlify.com)
2. Drag and drop project folder
3. Your site is live instantly!

### GitHub Pages
1. Create GitHub repository
2. Upload project files
3. Enable GitHub Pages in settings
4. Access at `https://yourusername.github.io/repo-name`

### Traditional Hosting
1. Upload files via FTP to your hosting provider
2. Point domain name to hosting server
3. Access via your domain

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 769px - 1199px
- **Mobile**: Below 768px
- **Small Mobile**: Below 480px

## 🔐 SEO & Meta Tags

Update in HTML head:
- `<title>` - Page title
- `<meta name="description">` - Page description
- `<meta property="og:image">` - Social media preview

## 📧 Contact Form Setup

For production, connect to a backend service:
- Formspree.io (Easy, free)
- SendGrid
- Mailgun
- Custom backend

## 🎯 Quick Wins for Enhancement

1. **Add Real Images**: Replace placeholder divs with actual photos
2. **Embed Google Map**: Use Google Maps embed API
3. **Add Testimonials**: Create student testimonials section
4. **Blog Section**: Add English learning tips blog
5. **Online Classes**: Add payment integration (Stripe, PayMongo)
6. **Student Dashboard**: Create login system for students
7. **Email Notifications**: Set up automated email responses

## 🔗 Important Files to Customize

| File | What to Change |
|------|---|
| index.html | Hero content, highlights, videos |
| about.html | Company story, team info, statistics |
| services.html | Programs, pricing, course details |
| contact.html | Address, phone, email, map |
| css/styles.css | Colors, fonts, layout |
| js/script.js | Form handling, interactions |

## 💡 Features in JavaScript

- Mobile menu toggle
- Form validation & submission
- Smooth scrolling
- Intersection Observer for animations
- Active navigation link highlighting
- Scroll-to-top button
- Count-up animation for statistics
- Phone number formatting

## 🎓 Template Variables (Mock Content)

The website includes mock content that should be updated:
- Student success stories (Videos)
- Program descriptions
- Testimonials
- Team members
- Pricing tiers

## 📞 Support for Further Customization

To customize further:
1. Edit HTML content directly
2. Modify CSS for styling changes
3. Update JavaScript for functionality
4. Add new sections by copying existing components

## 📜 License

This website template is provided as-is for Aurelia English Center's use.

## 🌐 Browser Support

- Chrome (Latest)
- Firefox (Latest)
- Safari (Latest)
- Edge (Latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🚀 Performance Tips

1. **Images**: Optimize before uploading (use TinyPNG or similar)
2. **Videos**: Use YouTube embeds (already optimized)
3. **CSS**: Already minified in production version
4. **JavaScript**: Already optimized for performance
5. **Caching**: Enable browser caching on server

---

**Created for**: Aurelia English Center 🇵🇭
**Location**: Koronadal City, Mindanao, Philippines
**Tagline**: "From Learning English to Learning In English"

Enjoy your stunning new website! ✨
