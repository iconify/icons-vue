<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="h9awd-him"/><path class="pxh7oumnf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:accessibility-alt-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.h9awd-him {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M11 5a1 1 0 1 1 2 0a1 1 0 0 1-2 0");
}

.pxh7oumnf {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 10h14m-7 0v4l-4 6m4-6l4 6M11 5a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>
