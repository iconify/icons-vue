<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGeimtbb7e)" class="r4i437pya"/><path class="aoxflhb5s"/></g><defs><linearGradient id="SVGeimtbb7e" x1="12" x2="12" y1="4" y2="20" gradientUnits="userSpaceOnUse"><stop class="ixn5c2bso"/><stop offset="1" class="yuo4ptbrl"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ktc-background" /></template>
<style>
.aoxflhb5s {
  fill: var(--svg-color--fff, #fff);
  d: path("M4.286 4v2.286H6.57V4zm0 16V7.429H6.57v6.56L16.514 4h3.2zm7.143-5.086A670 670 0 0 1 16.514 20h3.2l-6.605-6.857z");
}

.ft5dv1b6b {
  fill: none;
}

.ixn5c2bso {
  stop-color: var(--svg-color--53f3ff, #53f3ff);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.yuo4ptbrl {
  stop-color: var(--svg-color--38cdee, #38cdee);
}

</style>
