<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lau-pybjv"/><path class="a6k62accz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lightbulb-schedule" /></template>
<style>
.a6k62accz {
  d: path("M18 16.5V18l1.25 1");
}

.lau-pybjv {
  d: path("M6.5 15c0-1.75-3-3-3-6.5a6 6 0 0 1 12 0c0 3.5-3 4.75-3 6.5Zm.5 3h4.9m2.85 0a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
