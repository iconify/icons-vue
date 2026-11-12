<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xcv31pbge"/><path class="pecyojbct"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-bar-stacked-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.pecyojbct {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 20v-5a4 4 0 0 1 4-4h2V7a3 3 0 0 1 6 0v1h2a4 4 0 0 1 4 4v8zm6 0v-9m6 9V8M3 15h6m0-3h6m0 2h6");
}

.xcv31pbge {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9 6a3 3 0 1 1 6 0v14a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1Zm13 4v10a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1V10a3 3 0 0 1 6 0M2 13a3 3 0 0 1 6 0v7a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Z");
}

</style>
