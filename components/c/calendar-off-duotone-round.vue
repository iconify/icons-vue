<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="tzk3xjh0l"/><path class="lxk5_1_fy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-off-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.lxk5_1_fy {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19.284 19.284A4 4 0 0 1 16 21H8a4 4 0 0 1-4-4V9c0-1.36.679-2.561 1.716-3.284M11 5h5a4 4 0 0 1 4 4v5M4 9h5m6 0h5m-4-6v2M2 2l20 20");
}

.tzk3xjh0l {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M11 5h5a4 4 0 0 1 4 4h-5ZM9 9H4c0-1.313.636-2.537 1.716-3.284Z");
}

</style>
