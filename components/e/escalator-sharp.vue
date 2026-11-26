<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="rxe9ulb1w"/><path class="y1y3j_bom"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:escalator-sharp" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rxe9ulb1w {
  d: path("M4 7L4 8L4 11L4 12M2 18C2 16.3431 3.3431 15 5 15L6.7573 15L14.7574 7L19 7C20.6569 7 22 8.3431 22 10C22 11.6569 20.6569 13 19 13L17.2427 13L9.2426 21L5 21C3.3431 21 2 19.6569 2 18Z");
}

.y1y3j_bom {
  fill: currentColor;
  d: path("M5.5 3.5C5.5 4.3284 4.8284 5 4 5C3.1716 5 2.5 4.3284 2.5 3.5C2.5 2.6716 3.1716 2 4 2C4.8284 2 5.5 2.6716 5.5 3.5Z");
  stroke: none;
}

</style>
