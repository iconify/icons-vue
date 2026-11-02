<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="l5vv-kb4g"/><path class="zl-nrpb-q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cpu-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.l5vv-kb4g {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M10 6h4a4 4 0 0 1 4 4v4a4 4 0 0 1-4 4h-4a4 4 0 0 1-4-4v-4a4 4 0 0 1 4-4");
}

.zl-nrpb-q {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 10a4 4 0 0 1 4-4h4a4 4 0 0 1 4 4v4a4 4 0 0 1-4 4h-4a4 4 0 0 1-4-4Zm4-7v3m0 12v3M3 10h3m12 0h3m-7-7v3m0 12v3M3 14h3m12 0h3m-11-2a2 2 0 1 1 4 0a2 2 0 0 1-4 0");
}

</style>
