<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="f6q7pfwdl"/><path class="j_psw1y4g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circuit-board-duocolor-sharp" /></template>
<style>
.f6q7pfwdl {
  stroke-opacity: 0.4;
  d: path("M7 9a2 2 0 1 0 4 0a2 2 0 0 0-4 0m6 6a2 2 0 1 0 4 0a2 2 0 0 0-4 0m-2-6h6V3m-4 12H7v6");
}

.j_psw1y4g {
  d: path("M3 3h18v18H3Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
