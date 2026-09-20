<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGpsl5lcKR)" class="r4i437pya"/><path class="irreyj5nf"/><path class="q25_80zpo"/><path class="jdfmn8b1t"/></g><defs><linearGradient id="SVGpsl5lcKR" x1="3.996" x2="9.576" y1="5" y2="22.353" gradientUnits="userSpaceOnUse"><stop class="cga3zbn6n"/><stop offset="1" class="dl10_o4-g"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ctxc-background" /></template>
<style>
.cga3zbn6n {
  stop-color: var(--svg-color--307cc0, #307cc0);
}

.dl10_o4-g {
  stop-color: var(--svg-color--58bfdc, #58bfdc);
}

.ft5dv1b6b {
  fill: none;
}

.irreyj5nf {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.925 5.296c-.105-.245.28-.42.385-.185l7.485 13.134c-.13 0-.26-.045-.385-.065l-6.665-1.35c-.215-.01-.265-.37-.05-.425l2.61-.73a.216.216 0 0 0 .17-.215a.2.2 0 0 0-.02-.095l-3.53-10.074z");
}

.jdfmn8b1t {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.44 13.14c.13-.04.3.05.255.21c-.265.945-.55 1.885-.825 2.82c-.045.12.065.23.175.235c3.595.735 7.19 1.495 10.785 2.225c.07.01.115.065.17.11v.15l-.1.11H4.64c1.6-1.95 3.195-3.92 4.8-5.86");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q25_80zpo {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.54 5.315c.025.035.05.075.065.115c.79 2.28 1.6 4.56 2.385 6.84c.07.19-.195.35-.32.205c-.675-.715-1.315-1.45-1.975-2.17c-.105-.1-.26-.035-.33.07l-6.87 8.215c-.08.085-.15.215-.28.23c-.1 0-.16-.075-.215-.15v-.125c2.515-4.41 5.03-8.815 7.54-13.23");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
