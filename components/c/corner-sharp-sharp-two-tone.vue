<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="gwjgmfbqb"/><path class="bj190f85y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:corner-sharp-sharp-two-tone" /></template>
<style>
.bj190f85y {
  d: path("M9.5 3L21 3L21 14.5");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.gwjgmfbqb {
  stroke-opacity: 0.4;
  d: path("M3 7L3 6C3 4.3431 4.3431 3 6 3L7 3M21 17L21 18C21 19.6569 19.6569 21 18 21L17 21M14.5 21L9.5 21M7 21L6 21C4.3431 21 3 19.6569 3 18L3 17M3 14.5L3 9.5");
}

</style>
