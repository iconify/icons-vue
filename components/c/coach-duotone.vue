<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="v3gsxac3w"/><path class="axqputokj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:coach-duotone" /></template>
<style>
.axqputokj {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 18a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2h11a5 5 0 0 1 5 5v6a2 2 0 0 1-2 2M9 18h6M3 10h12M9 5v5m5-5l1 5v1a1 1 0 0 0 1 1h5M5 18a2 2 0 1 0 4 0a2 2 0 0 0-4 0m10 0a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

.ft5dv1b6b {
  fill: none;
}

.v3gsxac3w {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5 5h11a5 5 0 0 1 5 5v6a2 2 0 0 1-2 2a1.999 1.999 0 0 0-3-1.732c-.619.357-1 1.017-1 1.732H9a1.999 1.999 0 0 0-3-1.732c-.619.357-1 1.017-1 1.732a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2");
}

</style>
