<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="hnd7v4yjn"/><path class="uw3caobgb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:diagram-subtask-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.hnd7v4yjn {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 2L14 2C14.5523 2 15 2.4477 15 3L15 8C15 8.5523 14.5523 9 14 9L3 9C2.4477 9 2 8.5523 2 8L2 3C2 2.4477 2.4477 2 3 2ZM10 15L21 15C21.5523 15 22 15.4477 22 16L22 21C22 21.5523 21.5523 22 21 22L10 22C9.4477 22 9 21.5523 9 21L9 16C9 15.4477 9.4477 15 10 15Z");
  stroke: none;
}

.uw3caobgb {
  d: path("M6 8L6 18.5L10 18.5");
}

</style>
