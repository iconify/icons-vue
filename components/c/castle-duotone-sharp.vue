<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="cewbmcbks"/><path class="rjmlhed3b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:castle-duotone-sharp" /></template>
<style>
.cewbmcbks {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5 10V5a1 1 0 0 1 1-1h12a1 1 0 0 1 1 1v5h2a1 1 0 0 1 1 1v10a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V11a1 1 0 0 1 1-1Z");
}

.ft5dv1b6b {
  fill: none;
}

.rjmlhed3b {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 11h18v10H3zm3 0V3m12 8V3M6 5h12m-8-2v2m4-2v2M9 21v-3a3 3 0 0 1 6 0v3");
}

</style>
