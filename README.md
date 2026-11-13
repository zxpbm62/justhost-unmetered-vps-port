# Cheap Unmetered VPS: What Port Speed Really Caps You At, Which Plans to Skip, and JustHost's Full Price Table From $1.99

Unmetered means the host stopped counting gigabytes. It doesn't mean the pipe is unlimited, and a 10 Mbps port run flat out moves about 3.2 TB in a 30-day month, less than several metered plans hand you. JustHost prints the port speed on every plan card, so at least the trade-off is visible before you pay. Its best value on the current listing is Sirius: 1 core, 1 GB RAM, 20 GB NVMe and a 300 Mbps fair-share port for **$2.81/month**.

Below is every plan on JustHost's VPS tariff list with port speeds side by side, the arithmetic that turns Mbps into monthly terabytes, and three plans that a cheaper sibling on the same site beats outright.

> **Quick pick:** Sirius, $2.81/month. It costs a dollar less than New Star and gives three times the port speed plus double the disk. If 1 GB of RAM is too tight for your stack, Arcturus at $4.01 doubles the memory and the disk on the same 300 Mbps port. 👉 [Open the Sirius plan page](https://justhost.asia/en/services/vps/tariffs/sirius?ref=196392)

## Every JustHost VPS plan, port speed included

| Plan | vCPU / RAM | NVMe | Unmetered port (fair-share) | Price / 12-month rate | Order |
| --- | --- | --- | --- | --- | --- |
| VPS Promo | 1 core / 512 MB | 5 GB | 10 Mbps | $1.99 / n/a | [VPS Promo](https://justhost.asia/en/services/vps/tariffs/promo-c1r512nvme?ref=196392) |
| Sirius | 1 core / 1 GB | 20 GB | 300 Mbps | $2.81 / $2.25 | [Sirius](https://justhost.asia/en/services/vps/tariffs/sirius?ref=196392) |
| New Star | 1 core / 1 GB | 10 GB | 100 Mbps | $3.81 / $3.05 | [New Star](https://justhost.asia/en/services/vps/tariffs/new-star-c1r1024nvme?ref=196392) |
| Arcturus | 1 core / 2 GB | 30 GB | 300 Mbps | $4.01 / $3.21 | [Arcturus](https://justhost.asia/en/services/vps/tariffs/arcturus?ref=196392) |
| Double Star | 2 cores / 2 GB | 20 GB | 200 Mbps | $7.08 / $5.67 | [Double Star](https://justhost.asia/en/services/vps/tariffs/double-star-c2r2048nvme?ref=196392) |
| Vega | 2 cores / 4 GB | 80 GB | 500 Mbps | $7.79 / $6.23 | [Vega](https://justhost.asia/en/services/vps/tariffs/vega?ref=196392) |
| Alpha Centauri | 2 cores / 2 GB | 40 GB | 400 Mbps | $8.99 / $7.19 | [Alpha Centauri](https://justhost.asia/en/services/vps/tariffs/alpha_centauri?ref=196392) |
| Bright Star | 4 cores / 4 GB | 30 GB | 300 Mbps | $9.80 / $7.84 | [Bright Star](https://justhost.asia/en/services/vps/tariffs/bright-star-c4r4096nvme?ref=196392) |
| Yildun | 4 cores / 8 GB | 200 GB | 750 Mbps | $16.20 / $12.96 | [Yildun](https://justhost.asia/?ref=196392) |
| Capella | 4 cores / 4 GB | 120 GB | 750 Mbps | $18.30 / $14.64 | [Capella](https://justhost.asia/en/services/vps/tariffs/capella?ref=196392) |
| Betelgeuse | 6 cores / 12 GB | 400 GB | 750 Mbps | $26.40 / $21.12 | [Betelgeuse](https://justhost.asia/?ref=196392) |
| Altair | 8 cores / 24 GB | 600 GB | 750 Mbps | $47.40 / $37.92 | [Altair](https://justhost.asia/?ref=196392) |

Two things about those numbers. First, JustHost quotes two different prices for the same plan depending on which official page you land on: Sirius is $2.81 on the VPS landing page and $4.85 on the full tariff list, Arcturus is $4.01 versus $6.92, Vega $7.79 versus $13.44. The table shows the lower figure because that's the one the landing page advertises, but confirm the total on the checkout screen. Second, the 12-month column needs a minimum order of three months on New Star, Double Star and Bright Star; the discount is roughly 20%, and it is a billing-cycle discount rather than a coupon.

All ports are labelled fair-share, which matters more than the Mbps figure. Read on.

## What "unmetered" actually limits

Every unmetered plan has a ceiling; it just isn't measured in gigabytes. It's the port. Run the arithmetic on any plan and you get a hard monthly number, whether the host writes it down or not.

OVHcloud sells an unmetered VPS and states the model plainly: the traffic isn't measured, but the connection speed is fixed by the plan. Then, in a footnote, comes the part worth reading twice. Its Asia-Pacific locations (Mumbai, Singapore, Sydney) carry a monthly quota instead: 1 TB on VPS-1 and VPS-2, 3 TB on VPS-3 and VPS-4, 4 TB on VPS-5 and VPS-6, and past that the port is capped at 10 Mbps. That is an unmetered plan with a 1 TB cap on top, and the only place it's disclosed is the small print.

JustHost's equivalent disclosure is the word "fair-share" next to every port speed, plus its own translation into monthly volume: the 10 Mbps Promo is described as "4+ TB/mo", the 300 Mbps plans as "93+ TB/mo", the 750 Mbps plans as "232+ TB/mo". Those figures track the arithmetic in the next section within a few percent, so treat them as the honest ceiling rather than marketing.

And the ceiling is not a floor. A reviewer on the brand's Trustpilot page describes renting a "1000 Mbit channel" and getting 100–200 Mbps with dropouts under load. Fair-share means you draw from a shared pipe, and a 300 Mbps label is a cap under contention, not a reservation.

## How much traffic each port actually gives you

Multiply the port speed by 86,400 seconds, divide by 8 to get bytes, then multiply by 30 days. These are theoretical ceilings at 100% saturation, before protocol overhead.

| Port speed | Per day at full saturation | Per 30 days |
| --- | --- | --- |
| 10 Mbps | 108 GB | 3.2 TB |
| 100 Mbps | 1.08 TB | 32 TB |
| 200 Mbps | 2.16 TB | 65 TB |
| 300 Mbps | 3.24 TB | 97 TB |
| 400 Mbps | 4.32 TB | 130 TB |
| 500 Mbps | 5.4 TB | 162 TB |
| 750 Mbps | 8.1 TB | 243 TB |
| 1 Gbps | 10.8 TB | 324 TB |
| 2 Gbps | 21.6 TB | 648 TB |
| 10 Gbps | 108 TB | 3.24 PB |

The practical use of this table is working backwards. If your workload is 8 TB a month of video relays, a 100 Mbps plan gives you 32 TB of headroom and a 10 Mbps plan cannot physically serve you, no matter what the word "unmetered" suggests. If you're running a proxy for a handful of users, 300 Mbps is already far more than you'll consume and the RAM and disk matter more than the port.

👉 [See every JustHost plan with its port speed on one page](https://justhost.asia/en/services/vps/tariffs-all?ref=196392)

## Why the cheap unmetered plans are cheap

Compare cost per Mbps rather than cost per plan. FDC Servers publishes a clean ladder: $6.99/month for an unmetered 10 Mbps box and $24.99/month for an unmetered 1 Gbps box. That's **$0.70 per Mbps** at the bottom and **$0.025 per Mbps** at the $24.99 tier, a 28-fold difference for the same word on the label. Nothing about the $6.99 plan is a bargain in bandwidth terms; it's a cheap server with a slow port.

JustHost sits further down that curve. Sirius at $2.81 for a 300 Mbps fair-share port works out to about **$0.0094 per Mbps**, roughly a third of FDC's 1 Gbps price. The gap isn't a discount, it's a different product: a share of a big pipe with an AUP behind it, versus a stated port speed on a specific plan. Whether that trade suits you depends on whether you need sustained throughput or just a fast ceiling for bursts.

This is also why the "unmetered VPS from $2" listings you'll find in comparison roundups shouldn't be read as gigabit deals. The ten providers on HostAdvice's current unmetered list start between $2.00 and $11.21, all with 30-day refunds, and the same guide tells readers to "confirm that 'unmetered' truly means no caps or hidden fair-use policies." At $2 to $11 you're buying an entry container with a modest port, not dedicated bandwidth.

## Three JustHost plans a cheaper sibling beats

Sort the table by what you get rather than by price and three plans stop making sense.

**New Star ($3.81)** gives 1 core, 1 GB RAM, 10 GB NVMe and a 100 Mbps port. **Sirius ($2.81)** gives the same core count and RAM, 20 GB of disk and a 300 Mbps port for a dollar less. Unless the landing-page special disappears, there is no reason to order New Star.

**Alpha Centauri ($8.99)** gives 2 cores, 2 GB RAM, 40 GB and 400 Mbps. **Vega ($7.79)** gives 2 cores, 4 GB RAM, 80 GB and 500 Mbps for $1.20 less. Same story.

**Capella ($18.30)** gives 4 cores, 4 GB RAM, 120 GB and a 750 Mbps port. **Yildun ($16.20)** gives 4 cores, 8 GB RAM, 200 GB and the same 750 Mbps port, cheaper on both the monthly and 12-month rates.

The caveat is that the lower prices are the ones JustHost's VPS landing page advertises as specials; on the full tariff list Sirius reverts to $4.85 and New Star at $3.81 becomes the cheaper option again. Check which price the cart applies before you commit.

What about the $1.99 Promo? It's 512 MB of RAM and 5 GB of NVMe. After the operating system there's barely room for logs, so it works as a proxy endpoint, a monitoring node or a DNS box, and not much else. The step up to Sirius costs $0.82 a month and buys 4× the RAM, 4× the disk and 30× the port.

If you want the RAM and disk without paying twice, Vega is the sweet spot in the middle of the range. 👉 [Open the Vega plan page](https://justhost.asia/en/services/vps/tariffs/vega?ref=196392)

## What you're buying into beyond the port

JustHost's own description of itself on Trustpilot claims 45 server locations, NVMe storage, unlimited traffic, free SSL, IPv4 and IPv6, DDoS protection, root access and CN2-optimised routing for mainland China, with VPS from $2.25/month. A third-party review of the Hong Kong line from April 2026 describes KVM virtualisation, NVMe arrays, 300 Mbps to 1 Gbps ports, one IPv4 plus one IPv6, and a control panel with one-click data-centre and IP switching. The same review calls CPU performance average and notes that outbound routing runs through the US, so a relay is worth considering for latency-sensitive work. Payment methods listed there include crypto, cards, PayPal, Alipay and UnionPay.

Support is the weak point in public feedback. Reviews on the brand's Trustpilot page describe tickets answered days late, a full outage on 2 March 2026 with no status page, and one case where a location change from Amsterdam to Helsinki was needed to restore download speed. At this price point you're buying self-managed infrastructure and you should plan to be your own sysadmin.

Where the alternatives sit, for reference only: FDC Servers runs Linux only (Ubuntu, Alma, Rocky, Debian), is self-managed, and charges $24.99 for 2 CPU cores, 4 GB RAM, 100 GB NVMe and a 1 Gbps port, with 10 Gbps starting at $199.99. BlackHOST's cheapest 1 Gbps plan is $39.99 for 2 vCores, 4 GB and 100 GB NVMe, and it describes that bandwidth as guaranteed dedicated. OVHcloud supports both Windows and Linux and scales to 2 Gbps, with the Asia-Pacific quota caveat above. None of JustHost's listed plans exceed a 750 Mbps fair-share port, so a hard requirement for a full gigabit rules it out.

## Before you pay

1. Confirm the port speed in writing on the plan page or the order confirmation, not just in the marketing copy.
2. Read the acceptable-use section for throttling language. "Fair-share" plus an AUP is where overage behaviour is defined, whether that's a speed cap or a suspension.
3. Check which price the cart applies, given the gap between the landing page and the tariff list.
4. Ask for the renewal price and the refund window in writing. The plan cards show monthly and 12-month rates only, and neither number tells you what year two costs.
5. Pick the location before the plan. A fast port in the wrong region loses to a slow one next to your users, and JustHost's panel supports switching data centres after deployment.

Final rule: a proxy, a monitor or a single small service, take Sirius at $2.81 or the $1.99 Promo if 512 MB is genuinely enough. Two or more services, or anything with a database, start at Arcturus ($4.01) and go to Vega ($7.79) once you want 4 GB of RAM and an 80 GB disk. Sustained multi-terabyte traffic, Yildun at $16.20 is the cheapest way to a 750 Mbps port with room to store something.

👉 [Start with Sirius, or compare the full JustHost VPS line](https://justhost.asia/?ref=196392)
