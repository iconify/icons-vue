<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="y02rsxs5k"/><path class="s-jbknb7n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:align-center-vertical-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.s-jbknb7n {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 4a3 3 0 0 0-3 3v10a3 3 0 0 0 6 0V7a3 3 0 0 0-3-3m10 2a3 3 0 0 0-3 3v6a3 3 0 0 0 6 0V9a3 3 0 0 0-3-3M3 12h18");
}

.y02rsxs5k {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M11 7v10a4 4 0 0 1-8 0V7a4 4 0 0 1 8 0m10 2v6a4 4 0 0 1-8 0V9a4 4 0 0 1 8 0");
}

</style>
