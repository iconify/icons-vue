<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="p7xwi5beg"/><path class="djdsqac2p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:crab" /></template>
<style>
.djdsqac2p {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 13.75h.01m3.99 0h.01");
}

.p7xwi5beg {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 15a6.25 4.25 0 1 0 12.5 0a6.25 4.25 0 1 0-12.5 0m2-3.25L6 8.25m10.25 3.5L18 8.25M5.75 15.5H3m3.5 2.75L4 19.75m14.25-4.25H21m-3.5 2.75l2.5 1.5M6 8.25A2.75 2.75 0 0 1 3.5 4.5L5.25 6l1-2.25A2.75 2.75 0 0 1 6 8.25m12 0a2.75 2.75 0 0 0 2.5-3.75L18.75 6l-1-2.25a2.75 2.75 0 0 0 .25 4.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
