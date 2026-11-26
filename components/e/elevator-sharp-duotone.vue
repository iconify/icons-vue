<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="m2jc8whnu"/><path class="pgh3yypae"/><path class="isy2lrdil"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:elevator-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.isy2lrdil {
  fill: currentColor;
  d: path("M9.5 7.5C9.5 8.3284 8.8284 9 8 9C7.1716 9 6.5 8.3284 6.5 7.5C6.5 6.6716 7.1716 6 8 6C8.8284 6 9.5 6.6716 9.5 7.5Z");
  stroke: none;
}

.m2jc8whnu {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M15 12L15 21C15 21.5523 14.5523 22 14 22L2 22C1.4477 22 1 21.5523 1 21L1 3C1 2.4477 1.4477 2 2 2L14 2C14.5523 2 15 2.4477 15 3Z");
  stroke: none;
}

.pgh3yypae {
  d: path("M8 12L8 13M8 13L6 17L5.7236 17.5528M8 13L10 17L10.2764 17.5528M5 12L6 12L8 12L10 12L11 12M20 3L20 21M22.2929 5.2929L22 5L20 3L18 5L17.7071 5.2929M22.2929 18.7071L22 19L20 21L18 19L17.7071 18.7071");
}

</style>
