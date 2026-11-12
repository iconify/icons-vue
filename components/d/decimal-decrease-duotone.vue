<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="abw8qkbfh"/><path class="bjs4labdk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:decimal-decrease-duotone" /></template>
<style>
.abw8qkbfh {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M16 5v2a3 3 0 1 1-6 0V5a3 3 0 1 1 6 0");
}

.bjs4labdk {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 5a2 2 0 1 1 4 0v2a2 2 0 1 1-4 0ZM7 9h.01M6 15l-3 3l3 3m-3-3h18");
}

.ft5dv1b6b {
  fill: none;
}

</style>
