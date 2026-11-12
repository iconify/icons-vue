<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="cl-ln1hht"/><path class="uqsxp0b8v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-edit-corner-duotone-sharp" /></template>
<style>
.cl-ln1hht {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 2h18a1 1 0 0 1 1 1v8a1 1 0 0 1-1 1h-9v9a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1m11 19v-3l4-4l3 3l-4 4Z");
}

.ft5dv1b6b {
  fill: none;
}

.uqsxp0b8v {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 21H3V3h18v8M3 17l6-6l2 2m3-5a1 1 0 1 0 2 0a1 1 0 0 0-2 0m0 13v-3l4-4l3 3l-4 4Z");
}

</style>
