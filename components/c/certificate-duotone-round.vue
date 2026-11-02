<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="w71g6db2h"/><path class="t2y3wumjk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:certificate-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.t2y3wumjk {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 17H7a4 4 0 0 1-4-4V7a4 4 0 0 1 4-4h10a4 4 0 0 1 4 4v10M7 7h10M7 11h2m4 4a2.828 2.828 0 1 1 4-4a2.828 2.828 0 0 1-4 4m0 0v6l2-2l2 2v-6");
}

.w71g6db2h {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7 3h10a4 4 0 0 1 4 4v6a4 4 0 0 1-4 4v4l-2-2l-2 2v-4H7a4 4 0 0 1-4-4V7a4 4 0 0 1 4-4m10 14v-2h-4v2Z");
}

</style>
