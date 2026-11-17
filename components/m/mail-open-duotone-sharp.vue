<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="kon_4uh-g"/><path class="jtvdbkyfu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-open-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jtvdbkyfu {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m12 3l9 6v12H3V9zM3 9l6 6h6l6-6");
}

.kon_4uh-g {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M21 9v12H3V9l9-6Z");
}

</style>
