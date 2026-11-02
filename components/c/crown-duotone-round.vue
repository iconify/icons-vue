<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="e5_7bnb3d"/><path class="hxmqeacjo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:crown-duotone-round" /></template>
<style>
.e5_7bnb3d {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m16 10l5-4l-1.403 7.716A4 4 0 0 1 15.662 17H8.338a4 4 0 0 1-3.935-3.284L3 6l5 4l4-6Z");
}

.ft5dv1b6b {
  fill: none;
}

.hxmqeacjo {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m12 4l4 6l5-4l-1.403 7.716A4 4 0 0 1 15.662 17H8.338a4 4 0 0 1-3.935-3.284L3 6l5 4zM5 21h14");
}

</style>
