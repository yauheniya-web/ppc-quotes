PPC Quotes — iPhone web app (version 1.0)

Files: index.html, app.js, icon.png, manifest.webmanifest, sw.js

QUICK START ON COMPUTER
Open index.html in a desktop browser. Saving quotes uses local browser storage.

INSTALL ON IPHONE AS AN APP
1. Publish the COMPLETE folder to an HTTPS static host (GitHub Pages, Netlify, Cloudflare Pages).
2. Open the HTTPS address with Safari on iPhone.
3. Tap Share -> Add to Home Screen -> Add.
4. Open PPC Quotes from the icon on the home screen.

The application is a PWA. Once installed and opened online, the service worker caches it for offline use (except a first launch, which needs network access). No App Store account is required. A local downloaded HTML file is NOT equivalent to installing a PWA from an HTTPS site.

PDF ON IPHONE
Tap Create PDF. The Safari/iOS native print interface will open; use Share / Save to Files from its preview. In desktop browsers choose "Save as PDF" in print destination. PDF contains only the finalized client prices and descriptions, not discount information.

BACKUPS
Quotes remain on the device/browser in localStorage; they are not synced across devices. Periodically use "Export JSON backup". To move to another device, import this JSON backup.

PRICING
All prices are a user-editable business proposal concept based on the requested starting rate card, not a regulated market tariff. E3 and budgets above EUR 15k need custom quoting. The % fee formula uses the actual Google Ads monthly budget entered as an estimate; final contract should use agreed definition of actual spend. Currency EUR. Any applicable VAT, taxes and agency fees are not included.

DATA PRIVACY
No server or cloud storage is implemented. Browser data can be removed by clearing site data; keep backups. The proposal includes only client name, any entered contact, supplier details, service lines, terms and final prices.

LIMITATIONS IN V1
PDF is generated with iOS native Print -> Save to Files, not a dedicated single-click PDF-download engine. Discount is applied to a chosen scope (one-off, monthly, or first period only). First-period-only adjustments do not apply to later renewals; the PDF reflects the initial-period agreed price, so future-period pricing terms should be explicitly clarified before contracting.
