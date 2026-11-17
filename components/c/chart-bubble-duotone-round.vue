<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="yepu89uip"/><path class="w7ol9fg8f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-bubble-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.w7ol9fg8f {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14 7a3 3 0 1 0 6 0a3 3 0 0 0-6 0m-6 6a2 2 0 1 0 4 0a2 2 0 0 0-4 0m8 2a1 1 0 1 0 2 0a1 1 0 0 0-2 0M3 4v12a4 4 0 0 0 4 4h14");
}

.yepu89uip {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M14 7a3 3 0 1 1 6 0a3 3 0 0 1-6 0m-6 6a2 2 0 1 1 3.999-.001A2 2 0 0 1 8 13m8 2a1 1 0 1 1 2 0a1 1 0 0 1-2 0");
}

</style>
