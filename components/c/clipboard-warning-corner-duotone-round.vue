<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="uvn5gobiw"/><path class="cn4-rxbno"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clipboard-warning-corner-duotone-round" /></template>
<style>
.cn4-rxbno {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 5a4 4 0 0 0-4 4v8a4 4 0 0 0 4 4M19 9a4 4 0 0 0-4-4M9 5a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2M9 5a2 2 0 0 0 2 2h2a2 2 0 0 0 2-2m2 9v4m0 3h.01");
}

.ft5dv1b6b {
  fill: none;
}

.uvn5gobiw {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M13 9a4 4 0 0 0-4 4v8a4 4 0 0 1-4-4V9a4 4 0 0 1 4-4h6a4 4 0 0 1 4 4Z");
}

</style>
