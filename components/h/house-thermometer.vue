<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g_o3_obbf"/><path class="h2vvt1b0q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:house-thermometer" /></template>
<style>
.g_o3_obbf {
  d: path("M13.244 20.5H3.5v-10L12 3.25l8.5 7.25v1.356");
}

.h2vvt1b0q {
  d: path("M17 18v-3a1 1 0 0 1 2 0v3a2 2 0 1 1-2 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
