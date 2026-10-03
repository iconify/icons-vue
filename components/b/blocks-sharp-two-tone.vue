<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="yurbrxbff"/><path class="y00iszb8m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:blocks-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.y00iszb8m {
  d: path("M3 5L11 5L11 13L19 13L19 21L3 21L3 5ZM3 13L11 13M11 13L11 21M15 3L21 3L21 9L15 9L15 3Z");
}

.yurbrxbff {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M3 4L11 4C11.5523 4 12 4.4477 12 5L12 12L19 12C19.5523 12 20 12.4477 20 13L20 21C20 21.5523 19.5523 22 19 22L3 22C2.4477 22 2 21.5523 2 21L2 5C2 4.4477 2.4477 4 3 4ZM15 2L21 2C21.5523 2 22 2.4477 22 3L22 9C22 9.5523 21.5523 10 21 10L15 10C14.4477 10 14 9.5523 14 9L14 3C14 2.4477 14.4477 2 15 2Z");
  stroke: none;
}

</style>
