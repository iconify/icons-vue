<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="x9-6fslrl"/><path class="eca_cc7ap"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:kite-duotone-round" /></template>
<style>
.eca_cc7ap {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m17 13l-4 4a1.414 1.414 0 0 1-2 0l-7-7c-.517-.517.448-1.965 2-3l6-4l6 4c1.552 1.035 2.517 2.483 2 3zm-5-9v13M4 9h16m-8 9c0 3 5 3 7 3");
}

.ft5dv1b6b {
  fill: none;
}

.x9-6fslrl {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M13.707 17.707a2.414 2.414 0 0 1-3.414 0l-7-7c-.2-.2-.335-.451-.396-.727c-.324-1.472 1.468-3.092 2.548-3.812l6-4a1 1 0 0 1 1.11 0l6 4c1.08.72 2.872 2.34 2.548 3.812a1.47 1.47 0 0 1-.396.727Z");
}

</style>
