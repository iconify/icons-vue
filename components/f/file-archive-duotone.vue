<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="x9vmpf0uk"/><path class="lm1m17bnv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-archive-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.lm1m17bnv {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 3H7a2 2 0 0 0-2 2v16M19 9v10a2 2 0 0 1-2 2h-2M13 3l6 6m-6-6v4a2 2 0 0 0 2 2h4m-9-3h.01M8 8h.01M10 10h.01M8 12h.01M10 16a2 2 0 0 1 2 2v2a1 1 0 0 1-1 1H9a1 1 0 0 1-1-1v-2a2 2 0 0 1 2-2");
}

.x9vmpf0uk {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 5a3 3 0 0 1 3-3h6c.265 0 .52.105.707.293l6 6A1 1 0 0 1 20 9v10a3 3 0 0 1-3 3h-2a1 1 0 0 1-1-1v-3a4 4 0 0 0-8-.003V18a1 1 0 0 1-2 0Zm9 2a2 2 0 0 0 2 2h3l-5-5Z");
}

</style>
