<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="tjkod6arc"/><path class="gayn_pb9f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hospital-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gayn_pb9f {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 21h18M5 21V7a4 4 0 0 1 4-4h6a4 4 0 0 1 4 4v14m-9 0v-2a2 2 0 1 1 4 0v2M9 10h6m-3-3v6");
}

.tjkod6arc {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5 22a1 1 0 0 1-1-1V7a5 5 0 0 1 5-5h6a5 5 0 0 1 5 5v14a1 1 0 0 1-1 1Z");
}

</style>
