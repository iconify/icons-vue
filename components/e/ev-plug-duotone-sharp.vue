<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="i3xjh9b0f"/><path class="zv69vkhdf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ev-plug-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.i3xjh9b0f {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M18 5a8.485 8.485 0 0 1 0 12a8.485 8.485 0 0 1-12 0A8.485 8.485 0 0 1 6 5Z");
}

.zv69vkhdf {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 5h12A8.485 8.485 0 1 1 6 5m2 4h.01M12 9h.01M16 9h.01M10 14h.01M14 14h.01");
}

</style>
