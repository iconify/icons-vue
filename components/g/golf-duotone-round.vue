<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="toskpsvsh"/><path class="j_w8y1b_f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:golf-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.j_w8y1b_f {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 11V7c0-1.838 2.162-2.919 4-2c1.648.824 1.648 3.176 0 4zm0 0v6m-4 2c0 1.105 1.79 2 4 2s4-.895 4-2");
}

.toskpsvsh {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9 7c0-.633.184-1.247.536-1.774a3.44 3.44 0 0 1 1.328-1.154c1.126-.563 2.463-.526 3.583.034A3.21 3.21 0 0 1 16.236 7a3.21 3.21 0 0 1-1.789 2.894l-4 2A1 1 0 0 1 9 11Z");
}

</style>
