<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="z1njx9pvr"/><path class="ejt8x3b7b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:book-open-duotone-round" /></template>
<style>
.ejt8x3b7b {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 20V9a4 4 0 0 1 4-4h1a4 4 0 0 1 4 4v5a3 3 0 0 1-3 3h-1c-1.28 0-2.36.36-3 1zm0 0V9a4 4 0 0 0-4-4H7a4 4 0 0 0-4 4v5a3 3 0 0 0 3 3h1c1.28 0 2.36.36 3 1z");
}

.ft5dv1b6b {
  fill: none;
}

.z1njx9pvr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M13 19v-9l-1-1a4 4 0 0 1 4-4h1a4 4 0 0 1 4 4v5a3 3 0 0 1-3 3h-1c-1.041 0-2.236.237-3 1ZM8 5a4 4 0 0 1 4 4l-1 1v9l-1-1c-.764-.763-1.959-1-3-1H6a3 3 0 0 1-3-3V9a4 4 0 0 1 4-4Z");
}

</style>
