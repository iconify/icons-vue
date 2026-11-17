<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="l7iu-abcn"/><path class="vqk9l8b5v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:engine-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.l7iu-abcn {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M21 11v6a1 1 0 0 1-1 1h-1a1 1 0 0 1-1-1a1 1 0 0 0-1-1h-2a1 1 0 0 0-1 1v2a1 1 0 0 1-1 1h-3l-2-4H7a1 1 0 0 1-1-1v-4l3-3h4l2 4h2a1 1 0 0 0 1-1a1 1 0 0 1 1-1h1a1 1 0 0 1 1 1");
}

.vqk9l8b5v {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 14v3a1 1 0 0 1-1 1h-1a1 1 0 0 1-1-1a1 1 0 0 0-1-1h-2a1 1 0 0 0-1 1v2a1 1 0 0 1-1 1h-3l-2-4H7a1 1 0 0 1-1-1v-4l3-3h4l2 4h2a1 1 0 0 0 1-1a1 1 0 0 1 1-1h1a1 1 0 0 1 1 1zM9 4h4m-2 0v4m-8 3v4m0-2h3");
}

</style>
