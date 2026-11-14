<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g7gf7cbzd"/><path class="w18xxwbvs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lucky-draw-box" /></template>
<style>
.g7gf7cbzd {
  d: path("M3 9.5h18v12H3Zm0 0l3-4h12l3 4Zm6.5-2h5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w18xxwbvs {
  d: path("M9.75 13.75c0-1.25 1-2 2.25-2s2.25.75 2.25 2S12 15 12 16.5m0 2.5h.01");
}

</style>
