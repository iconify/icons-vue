<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="zoch16lok"/><path class="wub-hd51s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:laptop-smartphone-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wub-hd51s {
  d: path("M4 14L4 2L20 2L20 5M10 18L2 18L2 14L10 14");
}

.zoch16lok {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M23 22C23 22.5523 22.5523 23 22 23L13 23C12.4477 23 12 22.5523 12 22L12 10C12 9.4477 12.4477 9 13 9L22 9C22.5523 9 23 9.4477 23 10L23 22ZM16 15L19 15L19 13L16 13L16 15Z");
  stroke: none;
}

</style>
