---
title: Cutaway documentation
layout: default
---

# Cutaway documentation

* TOC
{:toc}

## 1. Before you start

You need:

- your products, with a **SKU on every part variant** (customers search by reference);
- one **collection per machine**, containing the machine and every part that fits it. Automated collections by product tag work well (for example tag `machine-g8` on the grinder and its parts);
- for each machine you want to show exploded: a **drawing**, ideally an SVG or a PNG with a plain background, where the parts are spread apart.

## 2. Theme settings

Open **Online Store > Themes > Customize > Theme settings**.

| Group | What to set |
|---|---|
| Logo and favicon | Your logo and its width. Without a logo, the store name is shown. |
| Colors | Four color schemes. Each section lets you choose one. "Page color scheme" sets the page background. |
| Typography | Heading and body fonts, from the Shopify font library. |
| Layout | Page width and corner radius. |
| **Machines** | **Machine collections**: select the collections that represent a machine. On every product page and product row, Cutaway then shows "Fits:" with links to the machines the product belongs to. |
| Social media | Links shown in the footer. |

Cutaway ships with three presets: **Cutaway** (green enamel and brass), **Manual** (light gray-green, condensed type) and **Foundry** (kraft paper, cast-iron charcoal and oxide red).

## 3. A machine page with an exploded view

1. In the theme editor, open a product page and create a new template from it, for example `machine`.
2. In **Product information**, set **Exploded drawing** (upload your drawing) and **Assembly name** (for example "Motor and guards").
3. Add a **Part callout** block for each numbered part. In each block:
   - **Product**: the part sold separately;
   - **Part name**: shown when no product is selected;
   - **Horizontal position** and **Vertical position**: where the number sits on the drawing, in percent. In the editor, a grid every 10% helps you place it.
4. Assign the template to the machine product: in the product admin, **Theme template > machine**.

Numbers follow the order of the blocks. Reorder the blocks to renumber. A section accepts 50 blocks in total, product information blocks included: about 40 parts per machine with the default blocks.

**On the page:** customers switch between "Exploded view" and "Photos". Selecting a number opens the part panel (image, price, stock, machines it fits, add to cart) without leaving the page. The parts list below the drawing repeats every number and works without JavaScript.

**On phones:** the page opens with the machine's name, its price and a link to the buy buttons, then the drawing. The drawing keeps its proportions and scrolls sideways; the parts list shows number, name, price and the add button. Selecting a number scrolls to the part.

## 4. Home page

The default home page contains:

| Section | Use |
|---|---|
| Exploded view | Your flagship machine, drawing and callouts, with a button to its page. On large screens the heading sits beside the drawing, so both show on the first screen; **Text position on large screens** puts it above instead. |
| Collection list | Your machines, as plates with the product count. |
| Featured collection | A list of parts (for example "Parts in stock"). |
| Featured product | One product with its buy buttons. |
| Image with text | Your story. |
| Blog posts | Guides from a blog. |

## 5. Search by reference

The search field in the header is shown on every page. Predictive search matches product titles and **variant SKUs**, so "G8-03" finds the part directly. Keep references short and consistent.

## 6. Product rows

Collections, search results and recommendations show products as rows: image, title, reference, "Fits:", price and an **Add** button. A product with one variant is added in one click; a product with several variants shows **Choose** and opens its page.

## 7. Recommendations

Product pages include two recommendation sections:

- **Related**: works on every store;
- **Complementary**: only filled when you set complementary products in the Shopify Search & Discovery app. Without them, the section stays hidden.

## 8. Other templates

Cart page, collection with filters, search, blog and article, contact page, gift card with recipient form, password page and 404 are included.

## 9. Collections and filters

Collection and search pages list products as rows, with filters (availability, price, product type, vendor, variant options) and sorting. On phones, filters and sorting fold under a **Filter and sort** button. Filters come from the Shopify Search & Discovery app: add or remove them there.

## 10. FAQ

**Can I use Cutaway without a drawing?**
Yes. Without a drawing and part callouts, the product template shows the photos and the buy buttons like any product page. The exploded view section on the home page can also be removed.

**What format should my drawing be?**
Any image Shopify accepts. A wide drawing with a plain background and parts spread along one line works best, because callouts sit at the end of short lines. The drawing should not contain numbers: Cutaway adds them.

**How many parts can one machine show?**
A section holds 50 blocks in total. With the default product information blocks, that leaves about 40 part callouts per machine.

**How do I change the number of a part?**
Numbers follow the order of the part callout blocks. Drag a block up or down in the editor to renumber.

**Why is the complementary products section empty?**
It only shows products you set as complementary in the Search & Discovery app.

**Why does a part show "Choose" instead of "Add"?**
The part has several variants. Customers pick one on the part's page.

**Does the parts list work without JavaScript?**
Yes. Each row is a link and a regular add-to-cart form.
