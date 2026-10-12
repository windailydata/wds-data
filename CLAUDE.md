# WinDailySports working notes

- **New tools go on the homepage.** When a new tool or page ships on windailysports.com, add it to `wds_home_tools()` in the Code Snippets snippet "WinDaily – Homepage: hero + free tools showcase" (id 55) if it's relevant. Put it in the right group; a 5th value of `1` features it in "Hot right now" and first in its group. Also consider the Odds HQ hub (snippet 126) and the Sports Betting menu.
- Later: re-rank the homepage tools by real traffic (GA / Search Console) once the new tools have had time to collect data.
- **Unlisted pages stay off the homepage, menus and hubs.** Check a page's snippet header and robots tag before linking it anywhere. `/nfl-line-tracker/` (snippet 96) is private: noindex, no menu, link-only.
- **Every page carries partner offers.** Posts get them from snippet 33, pages from snippet 141 ("Offers on every page + click counting": end box + sticky bar, matched to the page topic, state-filtered). New tools must show offers too; add a high-intent CTA where the user finishes the task (like the optimizer's "play these lineups" box).
- **Affiliate KPI = GA4 `partner_click`** (real browsers only). ThirstyAffiliates click logs now skip bots (snippet 141), but older TA numbers are bot-heavy.
