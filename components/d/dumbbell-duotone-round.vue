<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="airo5ybgg"/><path class="n8itx3u-v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:dumbbell-duotone-round" /></template>
<style>
.airo5ybgg {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M10 7v10a3 3 0 1 1-6 0v-.171A3 3 0 0 1 2 14v-4c0-1.27.803-2.405 2-2.829V7a3 3 0 1 1 6 0m10 0v.171A3 3 0 0 1 22 10v4c0 1.27-.803 2.405-2 2.829V17a3 3 0 1 1-6 0V7a3 3 0 1 1 6 0");
}

.ft5dv1b6b {
  fill: none;
}

.n8itx3u-v {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 7a2 2 0 1 1 4 0v10a2 2 0 1 1-4 0Zm10 0a2 2 0 1 1 4 0v10a2 2 0 1 1-4 0ZM5 8a2 2 0 0 0-2 2v4a2 2 0 0 0 2 2m14-8a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2M9 12h6");
}

</style>
