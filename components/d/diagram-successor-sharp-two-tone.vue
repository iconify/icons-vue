<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="avxzc_4lt"/><path class="rrrbrgbtp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:diagram-successor-sharp-two-tone" /></template>
<style>
.avxzc_4lt {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 2L12 2C12.5523 2 13 2.4477 13 3L13 8C13 8.5523 12.5523 9 12 9L3 9C2.4477 9 2 8.5523 2 8L2 3C2 2.4477 2.4477 2 3 2ZM3 15L21 15C21.5523 15 22 15.4477 22 16L22 21C22 21.5523 21.5523 22 21 22L3 22C2.4477 22 2 21.5523 2 21L2 16C2 15.4477 2.4477 15 3 15Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rrrbrgbtp {
  d: path("M3 3L12 3L12 8L3 8L3 3ZM3 16L21 16L21 21L3 21L3 16ZM12 5.5L18 5.5L18 12M20.2929 9.7071L18 12L15.7071 9.7071");
}

</style>
