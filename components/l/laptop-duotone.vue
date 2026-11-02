<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="yr12signw"/><path class="ky7p4f6bw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:laptop-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ky7p4f6bw {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 16V6a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2v10M3 18a2 2 0 0 1 2-2h14a2 2 0 1 1 0 4H5a2 2 0 0 1-2-2");
}

.yr12signw {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5 17a1 1 0 0 1-1-1V6a3 3 0 0 1 3-3h10a3 3 0 0 1 3 3v10a1 1 0 0 1-1 1Z");
}

</style>
