<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="p53xcyb3q"/><path class="x9s61dnhj"/><path clip-rule="evenodd" class="h-i6m1bzz"/><path class="hgi0gmgbc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-bullet-sharp-duotone" /></template>
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

.hgi0gmgbc {
  d: path("M16 6L16 18");
}

.p53xcyb3q {
  stroke-opacity: 0.4;
  d: path("M3 2L3 21L22 21");
}

.x9s61dnhj {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18.5 9L16 9C15.4477 9 15 9.4477 15 10L15 14C15 14.5523 15.4477 15 16 15L21 15C21.5523 15 22 14.5523 22 14L22 10C22 9.4477 21.5523 9 21 9Z");
  stroke: none;
}

</style>
