<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="k7yhpmb1m"/><path class="wa9mr9u4f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hand-grab-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.k7yhpmb1m {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M8 12V9a2 2 0 0 1 2-2l2 2a2 2 0 0 1 2-2l2 2a2 2 0 1 1 4 0v6a6 6 0 0 1-6 6h-4a6 6 0 0 1-6-6v-3a2 2 0 0 1 2-2Z");
}

.wa9mr9u4f {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 12V9a2 2 0 1 1 4 0a2 2 0 1 1 4 0a2 2 0 1 1 4 0v6a6 6 0 0 1-6 6h-4a6 6 0 0 1-6-6v-3a2 2 0 1 1 4 0m4-3v3m4-3v3m-8 0v3");
}

</style>
