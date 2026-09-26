<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="mc8x2ab8f"/><path class="onazxrbux"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:buildings-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.mc8x2ab8f {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 5L9 5L9 2C9 1.4477 9.4477 1 10 1L22 1C22.5523 1 23 1.4477 23 2L23 22C23 22.5523 22.5523 23 22 23L2 23C1.4477 23 1 22.5523 1 22L1 6C1 5.4477 1.4477 5 2 5Z");
  stroke: none;
}

.onazxrbux {
  d: path("M10 2L22 2L22 22L10 22L10 2ZM10 22L2 22L2 6L10 6M14 5L14 9M14 11L14 15M18 5L18 9M18 11L18 15M6 9L6 13M6 15L6 19M14 22L14 18L18 18L18 22");
}

</style>
