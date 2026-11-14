<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g0yukiccf"/><path class="h_a6efzmd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:forex-board" /></template>
<style>
.g0yukiccf {
  d: path("M2.5 3h19v18h-19ZM6 7.5h5.5");
}

.h_a6efzmd {
  d: path("m15 8.5l1.75-1.75L18.5 8.5M6 12h5.5m3.5-1l1.75 1.75L18.5 11M6 16.5h5.5m3.5 1l1.75-1.75l1.75 1.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
