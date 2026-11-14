<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="on5l0gbkg"/><path class="q3n0_ouit"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:badge-pro" /></template>
<style>
.on5l0gbkg {
  d: path("M2 6h20v12H2Z");
}

.q3n0_ouit {
  d: path("M5 15V9h1.25a1.25 1.25 0 0 1 0 2.5H5m5.25 3.5V9h1.25a1.25 1.25 0 0 1 0 2.5h-1.25m1.25 0L13 15m2.75-3a1.5 3 0 1 0 3 0a1.5 3 0 1 0-3 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
