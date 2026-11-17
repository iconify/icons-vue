<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="auqns-xaz"/><path class="kt4rzrl9i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:life-buoy-duotone-sharp" /></template>
<style>
.auqns-xaz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6 6a8.487 8.487 0 1 1 12.002 12.003A8.487 8.487 0 0 1 6 6m9 9a4.243 4.243 0 1 0-6.001-6.001A4.243 4.243 0 1 0 15 15");
}

.ft5dv1b6b {
  fill: none;
}

.kt4rzrl9i {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 6a8.485 8.485 0 1 1 12 12A8.485 8.485 0 0 1 6 6m3 3a4.243 4.243 0 1 1 6 6a4.243 4.243 0 0 1-6-6M6 6l3 3m9-3l-3 3m3 9l-3-3m-9 3l3-3");
}

</style>
