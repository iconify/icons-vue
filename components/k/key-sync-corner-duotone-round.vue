<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="lp6_d09sv"/><path class="cx6ewwb1c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:key-sync-corner-duotone-round" /></template>
<style>
.cx6ewwb1c {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 9a2.828 2.828 0 1 0-4 4a2.828 2.828 0 0 0 4-4m0 0l6-6m-2.128 2.129l2 2M13 4l2 2m5 12a4.472 4.472 0 0 1-8 0m0 3v-3h3m-3-4a4.472 4.472 0 0 1 8 0m0-3v3h-3");
}

.ft5dv1b6b {
  fill: none;
}

.lp6_d09sv {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9.548 9.56a3.829 3.829 0 1 1-7.096 2.88a3.829 3.829 0 0 1 7.096-2.88");
}

</style>
