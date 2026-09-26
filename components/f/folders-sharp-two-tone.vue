<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="wumzwvbxe"/><path class="p5m34fvfk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:folders-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p5m34fvfk {
  d: path("M5 9L3 9L3 21L16 21L16 19M8 3L12 3L14 5L21 5L21 16L8 16L8 3Z");
}

.wumzwvbxe {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 2L12 2C12.2652 2 12.5196 2.1054 12.7071 2.2929L14.4142 4L21 4C21.5523 4 22 4.4477 22 5L22 16C22 16.5523 21.5523 17 21 17L8 17C7.4477 17 7 16.5523 7 16L7 3C7 2.4477 7.4477 2 8 2Z");
  stroke: none;
}

</style>
