<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ib9btq7ec"/><path class="w1yb_mb5t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:dumbbell-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ib9btq7ec {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5 6a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1v-2H4a1 1 0 0 1-1-1V9a1 1 0 0 1 1-1h1Zm10 0a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1v2h1a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1h-1v2a1 1 0 0 1-1 1h-2a1 1 0 0 1-1-1Z");
}

.w1yb_mb5t {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 6a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1Zm10 0a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1h-2a1 1 0 0 1-1-1ZM5 8H4a1 1 0 0 0-1 1v6a1 1 0 0 0 1 1h1m14-8h1a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1h-1M9 12h6");
}

</style>
