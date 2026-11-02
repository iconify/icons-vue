<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ivlf1wb7g"/><path class="x91hiab0z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:crown-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ivlf1wb7g {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m16 10l5-4l-2 11H5L3 6l5 4l4-6Z");
}

.x91hiab0z {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m12 4l4 6l5-4l-2 11H5L3 6l5 4zM5 21h14");
}

</style>
