# unspace-legal

Legal and safety pages for the **Unspace** iOS app, published by Zintex OÜ.

Served as a static site with GitHub Pages. Plain HTML plus one stylesheet — no build step, no dependencies.

| Page | URL path |
|---|---|
| Legal index | `/` |
| Privacy Policy | `/privacy.html` |
| Terms of Service | `/terms.html` |
| Community Guidelines | `/guidelines.html` |
| Child Safety (CSAE) | `/child-safety.html` |
| Deleting your account | `/delete-account.html` |

## Where these are referenced

- App Store Connect → App Privacy → Privacy Policy URL
- App Store Connect → App Information → License Agreement / support URLs
- In-app paywall (terms and privacy links) and Settings
- Google Play → child safety standards URL

Update the "Last updated" line in `build`-generated pages whenever the content changes materially.

## Editing

Edit the HTML directly. `style.css` is shared by every page.
