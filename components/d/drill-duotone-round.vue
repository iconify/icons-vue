<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="m9n9vybaw"/><path class="yckxvub5k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:drill-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.m9n9vybaw {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5 3h8c.856 0 1.667.36 2.236 1H17a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2h-1.764A3 3 0 0 1 13 11h-1v4.171A3.001 3.001 0 0 1 11 21H7a3 3 0 0 1-1-5.829V11H5a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3");
}

.yckxvub5k {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 6a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Zm4 4v6m4-6v6m-6 2a2 2 0 0 1 2-2h4a2 2 0 1 1 0 4H7a2 2 0 0 1-2-2M15 5h2a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1h-2m3-2h3");
}

</style>
