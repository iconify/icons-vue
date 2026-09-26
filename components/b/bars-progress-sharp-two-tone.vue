<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ki9xk50fb"/><path class="e3dmmdpkn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bars-progress-sharp-two-tone" /></template>
<style>
.e3dmmdpkn {
  d: path("M3 3L21 3L21 9L3 9L3 3ZM3 15L21 15L21 21L3 21L3 15ZM15 3L15 9M10 15L10 21");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ki9xk50fb {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 2L21 2C21.5523 2 22 2.4477 22 3L22 9C22 9.5523 21.5523 10 21 10L3 10C2.4477 10 2 9.5523 2 9L2 3C2 2.4477 2.4477 2 3 2ZM3 14L21 14C21.5523 14 22 14.4477 22 15L22 21C22 21.5523 21.5523 22 21 22L3 22C2.4477 22 2 21.5523 2 21L2 15C2 14.4477 2.4477 14 3 14Z");
  stroke: none;
}

</style>
