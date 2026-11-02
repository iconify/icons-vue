<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="i430hfhsf"/><path class="ejt8x3b7b"/></g>`;
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

.i430hfhsf {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9.293 18.707C8.737 18.152 7.749 18 7 18H6a4 4 0 0 1-4-4V9a5 5 0 0 1 5-5h1a4.99 4.99 0 0 1 4 1.998A4.99 4.99 0 0 1 16 4h1a5 5 0 0 1 5 5v5a4 4 0 0 1-4 4h-1c-.749 0-1.737.152-2.293.707l-2 2a1 1 0 0 1-1.414 0Z");
}

</style>
