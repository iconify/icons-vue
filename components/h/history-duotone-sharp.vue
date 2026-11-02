<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="k4if0pbic"/><path class="h3ff0kbzr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:history-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.h3ff0kbzr {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 16a8.944 8.944 0 1 0 0-8m4 0H4V4m8 4v4l3 3");
}

.k4if0pbic {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3.056 12a8.946 8.946 0 1 1 17.89 0a8.946 8.946 0 1 1-17.89 0");
}

</style>
