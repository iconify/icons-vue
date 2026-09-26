<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="sh7hjab2q"/><path clip-rule="evenodd" class="kqhe7jbbf"/><path class="bgktbgbir"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bed-sharp-duotone" /></template>
<style>
.bgktbgbir {
  d: path("M2 3L2 21M22 16L22 21");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.kqhe7jbbf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1 17L1 9L22 9C22.5523 9 23 9.4477 23 10L23 17Z");
  stroke: none;
}

.sh7hjab2q {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M1 17L1 9L5 9L5 5C5 4.4477 5.4477 4 6 4L12 4C12.5523 4 13 4.4477 13 5L13 9L22 9C22.5523 9 23 9.4477 23 10L23 17L1 17Z");
  stroke: none;
}

</style>
