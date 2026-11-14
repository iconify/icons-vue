<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="z-8gi-bra"/><path class="lyiaeuhaq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:heart-candle" /></template>
<style>
.lyiaeuhaq {
  d: path("m12 18l-2.5-2.5a1.75 1.75 0 0 1 2.5-2.25a1.75 1.75 0 0 1 2.5 2.25Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z-8gi-bra {
  d: path("M6 9h12v12.5H6Zm6-6.5c2.25 2 2.25 3.75 0 3.75S9.75 4.5 12 2.5Z");
}

</style>
