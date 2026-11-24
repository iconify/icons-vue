<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="qyd1fzbhy"/><path class="iclbx5sdr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:building-dome-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.iclbx5sdr {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 9h18M5 9c0-3.314 3.134-6 7-6s7 2.686 7 6M3 21h18M6 13v4m4-4v4m4-4v4m4-4v4");
}

.qyd1fzbhy {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M19 9H5c0-3.314 3.134-6 7-6s7 2.686 7 6");
}

</style>
