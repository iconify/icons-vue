<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ql5fobtnx"/><path class="js38_ihba"/><path clip-rule="evenodd" class="zoga1lc_b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:heater-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.js38_ihba {
  d: path("M18 9L18 17M14 9L14 17M10 9L10 17M9 7L9 6C9 5.2131 9.3705 4.4721 10 4C10.6295 3.5279 11 2.7869 11 2L11 1M14 7L14 6C14 5.2131 14.3705 4.4721 15 4C15.6295 3.5279 16 2.7869 16 2L16 1");
}

.ql5fobtnx {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18 21L6 21L6 23L4 23L4 21L2 21C1.4477 21 1 20.5523 1 20L1 5C1 4.4477 1.4477 4 2 4L22 4C22.5523 4 23 4.4477 23 5L23 20C23 20.5523 22.5523 21 22 21L20 21L20 23L18 23L18 21Z");
  stroke: none;
}

.zoga1lc_b {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7 10C7 10.5523 6.5523 11 6 11C5.4477 11 5 10.5523 5 10C5 9.4477 5.4477 9 6 9C6.5523 9 7 9.4477 7 10ZM7 14C7 14.5523 6.5523 15 6 15C5.4477 15 5 14.5523 5 14C5 13.4477 5.4477 13 6 13C6.5523 13 7 13.4477 7 14Z");
  stroke: none;
}

</style>
