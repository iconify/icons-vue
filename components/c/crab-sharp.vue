<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="sq5tk4bms"/><path class="djdsqac2p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:crab-sharp" /></template>
<style>
.djdsqac2p {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 13.75h.01m3.99 0h.01");
}

.sq5tk4bms {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 15a6.25 4.25 0 1 0 12.5 0a6.25 4.25 0 1 0-12.5 0Zm2-3.25L6 8.25m10.25 3.5L18 8.25M5.75 15.5H3m3.5 2.75L4 19.75m14.25-4.25H21m-3.5 2.75l2.5 1.5M6 8.25l-3.931-.088L3.5 4.5L5.25 6l1-2.25l3.092 2.429zm12 0l3.931-.088L20.5 4.5L18.75 6l-1-2.25l-3.092 2.429z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
