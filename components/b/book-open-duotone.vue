<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="w123cvs3c"/><path class="r-lqps64o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:book-open-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.r-lqps64o {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 20V9a4 4 0 0 1 4-4h3a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2h-3c-.64 0-1.36.36-2 1zm0 0V9a4 4 0 0 0-4-4H5a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h3c.64 0 1.36.36 2 1z");
}

.w123cvs3c {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9.293 18.707C8.98 18.395 8.468 18 8 18H5a3 3 0 0 1-3-3V7a3 3 0 0 1 3-3h3a4.99 4.99 0 0 1 4 1.998A4.99 4.99 0 0 1 16 4h3a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3h-3c-.468 0-.98.395-1.293.707l-2 2a1 1 0 0 1-1.414 0Z");
}

</style>
