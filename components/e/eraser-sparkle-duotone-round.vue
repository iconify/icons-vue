<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="khpm-rqcb"/><path class="v2pjf6bzm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:eraser-sparkle-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.khpm-rqcb {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6 3c.002 1.005 1.995 2.998 3 3c-1.005.002-2.998 1.995-3 3c-.002-1.005-1.995-2.998-3-3c1.005-.002 2.998-1.995 3-3m1 11l7-7a2.83 2.83 0 0 1 4 0l1 1a2.83 2.83 0 0 1 0 4l-8 8H7a4.24 4.24 0 0 1 0-6");
}

.v2pjf6bzm {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m15 16l4-4a2.83 2.83 0 0 0 0-4l-1-1a2.83 2.83 0 0 0-4 0l-4 4m0 0l-3 3a4.243 4.243 0 0 0 0 6h4l4-4m-4 4h10m-11-9l5 5M6 3c0 1 2 3 3 3c-1 0-3 2-3 3c0-1-2-3-3-3c1 0 3-2 3-3");
}

</style>
