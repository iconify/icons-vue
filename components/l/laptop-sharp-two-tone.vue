<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="u1xiz-p5r"/><path class="tg_uypbvb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:laptop-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tg_uypbvb {
  d: path("M4 16L4 4L20 4L20 16M2 16L22 16L22 20L2 20L2 16Z");
}

.u1xiz-p5r {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 15L3 4C3 3.4477 3.4477 3 4 3L20 3C20.5523 3 21 3.4477 21 4L21 15L22 15C22.5523 15 23 15.4477 23 16L23 20C23 20.5523 22.5523 21 22 21L2 21C1.4477 21 1 20.5523 1 20L1 16C1 15.4477 1.4477 15 2 15L3 15Z");
  stroke: none;
}

</style>
