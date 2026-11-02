<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="dmwl_vflh"/><path class="pecyojbct"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-bar-stacked-duotone-round" /></template>
<style>
.dmwl_vflh {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9 11V6a3 3 0 1 1 6 0v5a1 1 0 0 1-1 1h-4a.997.997 0 0 1-1-1m13-1v3a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1v-3a3 3 0 0 1 6 0M8 13v1a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-1a3 3 0 0 1 6 0m7 7a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1v-6a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1Zm6-5a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1v-4a1 1 0 0 1 1-1ZM2 17a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v3a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Z");
}

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

</style>
