<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="fc4an-b_z"/><path class="q_nez3b8z"/><path class="zf8a5_b0r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:ev-charger-sharp-duotone" /></template>
<style>
.fc4an-b_z {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14 23L2 23C1.4477 23 1 22.5523 1 22L1 2C1 1.4477 1.4477 1 2 1L14 1C14.5523 1 15 1.4477 15 2L15 21L23 21L23 23L14 23Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q_nez3b8z {
  d: path("M9.3 7.6L6 12L10 12L6.7 16.4M14 17L20 17L20 10M22 6L22 3M18 6L18 3");
}

.zf8a5_b0r {
  fill: currentColor;
  d: path("M18 5L22 5C22.5523 5 23 5.4477 23 6L23 10C23 10.5523 22.5523 11 22 11L18 11C17.4477 11 17 10.5523 17 10L17 6C17 5.4477 17.4477 5 18 5Z");
  stroke: none;
}

</style>
