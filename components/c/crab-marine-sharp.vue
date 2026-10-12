<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="wij5t4gnk"/><path class="e31_w5nyr"/><path class="w_js38bgq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:crab-marine-sharp" /></template>
<style>
.e31_w5nyr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.25 12.75h.01m3.49 0h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.w_js38bgq {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 3.09a2.5 2.5 0 1 0 .92 3.41L6.25 5.25Zm9 0a2.5 2.5 0 1 1-.92 3.41l2.17-1.25ZM7.6 7.6L9 10.4m7.4-2.8L15 10.4m-8.75 2.35L3 11.5M6.4 15H2.75m5.05 1.25L5.5 18.5m12.25-5.75L21 11.5M17.6 15h3.65m-5.05 1.25l2.3 2.25m-15.75 2c3-.75 6-.75 9.25 0s6.25.75 9.25 0");
}

.wij5t4gnk {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 13.75a6 3.5 0 1 0 12 0a6 3.5 0 1 0-12 0Z");
}

</style>
