# Whale Rider website preview

This repository contains a static, responsive storefront *preview* for Whale Rider.

## Important

- This is **not yet a live e-commerce store**. Product images, variant selections, checkout links, real shipping/tax calculation, privacy policy, returns policy, and order handling must be completed and tested.
- Prices are provisional and based on the initial site inventory snapshot. Verify against your Shopify export.
- Do not cancel Shopify or update DNS until the replacement storefront is live and tested.
- GitHub Pages is **not suitable for operating an e-commerce site** under its restrictions. Use Cloudflare Pages or another commerce-permitting host after reviewing its current terms.
- Do not commit payment API keys, Shopify exports containing customer data, or any secrets to this repository.

## Deploy preview on Cloudflare Pages

1. In Cloudflare, select Workers & Pages, create a Pages project, and connect the GitHub repository.
2. Select no framework (static HTML); use `/` for the output directory if prompted.
3. Deploy and inspect the `pages.dev` preview URL.
4. After building out products, connect real payment provider links and verify checkout, taxes, inventory, shipping, policies, and mobile usability.
5. Move your existing domain only after these checks succeed.

## Needed to finish

- Shopify product CSV export (products and variants)
- Original Whale Rider logo, product photos, and homepage imagery
- Final store policies, shipping settings and payment-provider account

The preview catalog intentionally disables buying to avoid misleading customers.
