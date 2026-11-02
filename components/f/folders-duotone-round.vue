<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="nhojs2bwx"/><path class="f6xyq5dog"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folders-duotone-round" /></template>
<style>
.f6xyq5dog {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 11h3a4 4 0 0 1 4 4v2a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4v-6a2 2 0 0 1 2-2h3zM7 5a2 2 0 0 1 2-2h3l2 2m0 0h3a4 4 0 0 1 4 4v6");
}

.ft5dv1b6b {
  fill: none;
}

.nhojs2bwx {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M10.414 10H13a5 5 0 0 1 5 5v2a5 5 0 0 1-5 5H7a5 5 0 0 1-5-5v-6a3 3 0 0 1 3-3h3c.265 0 .52.105.707.293Z");
}

</style>
