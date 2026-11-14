<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r-ftaqbgr"/><path class="mwa327vjc"/><path class="da4bjdb3m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lancet" /></template>
<style>
.da4bjdb3m {
  fill: currentColor;
  d: path("M7 13.75c.75 1 1.25 1.5 1.25 2C8.25 16.5 7.75 17 7 17s-1.25-.5-1.25-1.25c0-.5.5-1 1.25-2Z");
}

.mwa327vjc {
  d: path("m18.073 2.659l1.768 1.768l-1.414 1.414l-1.768-1.768ZM9.5 11.75L8 13.25M2.5 19.5c2-2 5.5-2 7.5 0");
}

.r-ftaqbgr {
  d: path("m16.298 2.52l3.182 3.182l-7.778 7.778l-3.182-3.182Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
