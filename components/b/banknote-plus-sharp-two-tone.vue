<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="lzr69co-j"/><path class="xrmvtbcqo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:banknote-plus-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.lzr69co-j {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 1L22 1C22.5523 1 23 1.4477 23 2L23 13L13 13L13 17L2 17C1.4477 17 1 16.5523 1 16L1 2C1 1.4477 1.4477 1 2 1Z");
  stroke: none;
}

.xrmvtbcqo {
  d: path("M22 13L22 2L2 2L2 16L13 16M14 9C14 10.1046 13.1046 11 12 11C10.8954 11 10 10.1046 10 9C10 7.8954 10.8954 7 12 7C13.1046 7 14 7.8954 14 9ZM16 6L19 6M8 12L5 12M19 15L19 23M23 19L15 19");
}

</style>
