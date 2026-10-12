<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="c6vt1lbds"/><path class="rrnp7cvhy"/><path class="c6hdcnbvq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:head-bandage-sharp" /></template>
<style>
.c6hdcnbvq {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.25 17.25l1-1.25h3.5l1 1.25M4.96 6h14.08a9.25 9.25 0 0 1 1.86 3.5H3.1A9.25 9.25 0 0 1 4.96 6Z");
}

.c6vt1lbds {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rrnp7cvhy {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 12h.01M15 12h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
