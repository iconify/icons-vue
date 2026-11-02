<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="j92nkubto"/><path class="x67wqzt2d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-bar-horizontal-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.j92nkubto {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M11 2a3 3 0 0 1 0 6H4a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1ZM3 14v-4a1 1 0 0 1 1-1h14a3 3 0 1 1 0 6H4a1 1 0 0 1-1-1m11 8H4a1 1 0 0 1-1-1v-4a1 1 0 0 1 1-1h10a3 3 0 0 1 0 6");
}

.x67wqzt2d {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 3h5a4 4 0 0 1 4 4v2h4a3 3 0 0 1 0 6h-1v2a4 4 0 0 1-4 4H4zm0 6h9m-9 6h12");
}

</style>
