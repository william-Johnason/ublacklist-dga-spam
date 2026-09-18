# ublacklist-dga-spam
A community-maintained uBlacklist subscription list designed to filter out programmatically generated DGA subdomains, low-quality content farms, and search-hijacking spam networks from Google and other search engines.


# uBlacklist DGA & Random Subdomain Spam Blocklist

A community-focused uBlacklist ruleset that automatically filters out programmatic DGA (Domain Generation Algorithm) spam subdomains, scrapers, and copycat sites from appearing in search engine results (Google, DuckDuckGo, Bing, etc.).

---

## Prerequisites: Install the uBlacklist Extension

Before subscribing to this list, ensure you have the **uBlacklist** extension installed in your web browser:

1. Open the [Chrome Web Store - uBlacklist](https://chromewebstore.google.com/detail/ublacklist/pncfbmialoiaghdehhbnbhkkgmjanfhe).
2. Click **Add to Chrome**.
3. (Optional) Click the puzzle icon in your browser toolbar and **pin** uBlacklist for quick access.

---

## How to Subscribe to This Blocklist

Choose one of the two methods below to install this blocklist.

### Option 1: Direct Installation (From This Repository)

If you want to subscribe directly to this repository right now:

1. Copy the raw ruleset URL:
   `https://raw.githubusercontent.com/william-Johnason/ublacklist-dga-spam/refs/heads/main/uBlacklist.txt`
2. Click the **uBlacklist icon** in your browser toolbar and choose **Options** (or right-click the icon and choose *Extension Options*).
3. Scroll down to the **Subscriptions** section.
4. Click **Add subscription**.
5. Paste the copied URL into the **URL** box. Specify **Name** as `DGA & Random Subdomain Spam Blocklist`.
6. Click **Add**.
7. Click **Update now** next to the newly added subscription to fetch the rules immediately.

---

### Option 2: Community Directory (One-Click Subscribe)

*Note: Available after our Pull Request is merged into the official directory.*

1. Open **uBlacklist Options** in your browser.
2. Scroll to **Subscriptions** and turn **ON** the toggle for **Enable ruleset subscription links**.
3. Visit the official [uBlacklist Community Rulesets Directory](https://ublacklist.github.io/rulesets).
4. Search for `DGA & Random Subdomain Spam Blocklist`.
5. Click the blue **`➕` (Plus)** button next to the entry to automatically subscribe.

---

## Contributing & Reporting Spam Sites

If you encounter new DGA subdomains or spam search results that are not yet caught by this list:

1. Open a [New GitHub Issue](https://github.com/william-Johnason/ublacklist-dga-spam/issues/new).
2. Provide the domain/subdomain URL.
3. Or submit a **Pull Request** adding your rule using the match pattern syntax (e.g., `*://*.example.site/*`).
