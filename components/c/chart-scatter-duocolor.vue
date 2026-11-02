<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nt-syvbnj"/><path class="t5ywm1l9h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-scatter-duocolor" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nt-syvbnj {
  stroke-opacity: 0.4;
  d: path("M3 4v14a2 2 0 0 0 2 2h16");
}

.t5ywm1l9h {
  d: path("M7 15a1 1 0 1 0 2 0a1 1 0 0 0-2 0m5-4a1 1 0 1 0 2 0a1 1 0 0 0-2 0m6 3a1 1 0 1 0 2 0a1 1 0 0 0-2 0m-2-8a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>
