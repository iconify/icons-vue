<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="h-i6m1bzz"/><path class="sv57d1blu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-bullet-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.h-i6m1bzz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.5 9L7 9C6.4477 9 6 9.4477 6 10L6 14C6 14.5523 6.4477 15 7 15L16 15C16.5523 15 17 14.5523 17 14L17 10C17 9.4477 16.5523 9 16 9Z");
  stroke: none;
}

.sv57d1blu {
  d: path("M3 2L3 21L22 21M7 10L21 10L21 14L7 14ZM16 6L16 18");
}

</style>
