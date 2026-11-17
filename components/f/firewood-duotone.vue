<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="hf8gpxl5s"/><path class="h38_8cc3m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:firewood-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.h38_8cc3m {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 5v6l-1 1a1.414 1.414 0 0 0 0 2l1 1v4c0 1.105 2.686 2 6 2s6-.895 6-2v-6l1-1a1.414 1.414 0 0 0 0-2l-1-1V5m-8 7v4M6 5c0-1.105 2.686-2 6-2s6 .895 6 2M6 5c0 1.105 2.686 2 6 2s6-.895 6-2");
}

.hf8gpxl5s {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6 5c0-1.105 2.686-2 6-2s6 .895 6 2v4l1 1a1.415 1.415 0 0 1 0 2l-1 1v6c0 1.105-2.686 2-6 2s-6-.895-6-2v-4l-1-1a1.415 1.415 0 0 1 0-2l1-1Z");
}

</style>
