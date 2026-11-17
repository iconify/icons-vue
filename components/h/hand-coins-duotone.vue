<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="gwwfllbjb"/><path class="rfdi0bc1o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hand-coins-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gwwfllbjb {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M16 7a2 2 0 1 1-.001-3.999A2 2 0 0 1 16 7M9 8a2 2 0 1 1-.001-3.999A2 2 0 0 1 9 8m-2 5c.559-.559 1.178-1 2-1h3a2 2 0 0 1 2 2l3-3a2.122 2.122 0 0 1 3 3l-5 5c-.521.52-1.237 1-2 1H8l-4-4Z");
}

.rfdi0bc1o {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m4 16l3-3c.6-.6 1.2-1 2-1h3a2 2 0 1 1 0 4h-2m4-2l3-3a2.121 2.121 0 1 1 3 3l-5 5c-.64.64-1.36 1-2 1H8m-5-5l6 6M7 6a2 2 0 1 0 4 0a2 2 0 0 0-4 0m7-1a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

</style>
