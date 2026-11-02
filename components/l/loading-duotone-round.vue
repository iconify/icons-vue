<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rjb55wb_o"/><path class="wlma3nbrc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:loading-duotone-round" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rjb55wb_o {
  stroke-opacity: 0.4;
  d: path("M11 12a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

.wlma3nbrc {
  d: path("M5 14a1 1 0 1 0 2 0a1 1 0 0 0-2 0m12-4a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>
