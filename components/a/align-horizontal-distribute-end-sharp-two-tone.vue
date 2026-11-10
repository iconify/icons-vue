<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="yx5onu4-m"/><path class="y0ku-2kxn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-horizontal-distribute-end-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.y0ku-2kxn {
  d: path("M20 1V23M10 1V23M4 8H10V16H4V8ZM20 4V20H14V4H20Z");
}

.yx5onu4-m {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11 23H9V17H4C3.448 17 3 16.552 3 16V8C3 7.448 3.448 7 4 7H9V1H11V23ZM21 23H19V21H14C13.448 21 13 20.552 13 20V4C13 3.448 13.448 3 14 3H19V1H21V23Z");
  stroke: none;
}

</style>
