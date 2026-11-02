<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="d21kzaboz"/><path class="rfdi0bc1o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hand-coins-duotone-round" /></template>
<style>
.d21kzaboz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M13.236 3.832a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338m-7 1a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338");
}

.ft5dv1b6b {
  fill: none;
}

.rfdi0bc1o {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m4 16l3-3c.6-.6 1.2-1 2-1h3a2 2 0 1 1 0 4h-2m4-2l3-3a2.121 2.121 0 1 1 3 3l-5 5c-.64.64-1.36 1-2 1H8m-5-5l6 6M7 6a2 2 0 1 0 4 0a2 2 0 0 0-4 0m7-1a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

</style>
