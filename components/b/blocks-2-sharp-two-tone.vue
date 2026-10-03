<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="u4s5hrjxf"/><path class="wr1t92zdx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:blocks-2-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u4s5hrjxf {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 11L6 2C6 1.4477 6.4477 1 7 1L17 1C17.5523 1 18 1.4477 18 2L18 11L22 11C22.5523 11 23 11.4477 23 12L23 22C23 22.5523 22.5523 23 22 23L2 23C1.4477 23 1 22.5523 1 22L1 12C1 11.4477 1.4477 11 2 11L6 11Z");
  stroke: none;
}

.wr1t92zdx {
  d: path("M7 12L7 2L17 2L17 12M2 12L22 12L22 22L2 22L2 12ZM12 12L12 22");
}

</style>
