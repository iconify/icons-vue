<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ed3kmcc7e"/><path class="w2zj2_9ae"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:diagram-predecessor-sharp-two-tone" /></template>
<style>
.ed3kmcc7e {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 15L12 15C12.5523 15 13 15.4477 13 16L13 21C13 21.5523 12.5523 22 12 22L3 22C2.4477 22 2 21.5523 2 21L2 16C2 15.4477 2.4477 15 3 15ZM3 2L21 2C21.5523 2 22 2.4477 22 3L22 8C22 8.5523 21.5523 9 21 9L3 9C2.4477 9 2 8.5523 2 8L2 3C2 2.4477 2.4477 2 3 2Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.w2zj2_9ae {
  d: path("M3 16L12 16L12 21L3 21L3 16ZM3 3L21 3L21 8L3 8L3 3ZM12 18.5L18 18.5L18 12M15.7071 14.2929L18 12L20.2929 14.2929");
}

</style>
