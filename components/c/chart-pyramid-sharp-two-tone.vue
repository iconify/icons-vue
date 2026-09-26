<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="f6r4a2bvx"/><path class="kx_7c83ot"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-pyramid-sharp-two-tone" /></template>
<style>
.f6r4a2bvx {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11.1258 2.5144L1.1258 20.5144C1.0433 20.6629 1 20.8301 1 21C1 21.5523 1.4477 22 2 22L22 22C22.5523 22 23 21.5523 23 21C23 20.8301 22.9567 20.6629 22.8742 20.5144L12.8742 2.5144C12.6978 2.1969 12.3632 2 12 2C11.6368 2 11.3022 2.1969 11.1258 2.5144Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.kx_7c83ot {
  d: path("M12 3L2 21L22 21L12 3ZM8.6667 9L15.3333 9M5.3333 15L18.6667 15");
}

</style>
