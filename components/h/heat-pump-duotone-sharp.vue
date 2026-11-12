<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="fh-5z_bry"/><path class="ft5d8ok9b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:heat-pump-duotone-sharp" /></template>
<style>
.fh-5z_bry {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M2 19V3a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v16a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1");
}

.ft5d8ok9b {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3h18v16H3Zm4 16v2m10-2v2M7 11a5 5 0 0 1 10 0m0 0a5 5 0 0 1-10 0m5 0c-2 0-2-5 0-5m0 5c0-2 5-2 5 0m-5 0c2 0 2 5 0 5m0-5c0 2-5 2-5 0");
}

.ft5dv1b6b {
  fill: none;
}

</style>
