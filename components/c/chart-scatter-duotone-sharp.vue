<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="vg5v31emn"/><path class="fbvnrr2dz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-scatter-duotone-sharp" /></template>
<style>
.fbvnrr2dz {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 15a1 1 0 1 0 2 0a1 1 0 0 0-2 0m5-4a1 1 0 1 0 2 0a1 1 0 0 0-2 0m6 3a1 1 0 1 0 2 0a1 1 0 0 0-2 0m-2-8a1 1 0 1 0 2 0a1 1 0 0 0-2 0M3 4v16h18");
}

.ft5dv1b6b {
  fill: none;
}

.vg5v31emn {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M17 7a1 1 0 1 1 0-2a1 1 0 0 1 0 2m-4 5a1 1 0 1 1 0-2a1 1 0 0 1 0 2m6 3a1 1 0 1 1 0-2a1 1 0 0 1 0 2M8 16a1 1 0 1 1 0-2a1 1 0 0 1 0 2");
}

</style>
