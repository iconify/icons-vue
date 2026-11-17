<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="y_0k3hbcr"/><path class="d7vof9bip"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-geothermal-duotone" /></template>
<style>
.d7vof9bip {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 15H8.667a2 2 0 0 1-2-2V8.574A2 2 0 0 1 7.35 7.07l3.333-2.917a2 2 0 0 1 2.634 0L16.65 7.07a2 2 0 0 1 .683 1.505V13a2 2 0 0 1-2 2zm0 0v4m-6 2v-2h12v2m-8-2v2m4-2v2");
}

.ft5dv1b6b {
  fill: none;
}

.y_0k3hbcr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M8.667 15a2 2 0 0 1-2-2V8.574a2 2 0 0 1 .683-1.505l3.333-2.917a2 2 0 0 1 2.634 0l3.333 2.917a2 2 0 0 1 .683 1.505V13a2 2 0 0 1-2 2Z");
}

</style>
