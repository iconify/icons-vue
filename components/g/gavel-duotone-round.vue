<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="m98d2cpaw"/><path class="sy3t2or1f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:gavel-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.m98d2cpaw {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m15 12l-8 8a2.122 2.122 0 0 1-3-3l8-8l-1-1a1.415 1.415 0 0 1 0-2l2-2a1.415 1.415 0 0 1 2 0l5 5a1.415 1.415 0 0 1 0 2l-2 2a1.415 1.415 0 0 1-2 0Z");
}

.sy3t2or1f {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m17 6l3 3a1.414 1.414 0 0 1 0 2l-2 2a1.414 1.414 0 0 1-2 0l-5-5a1.414 1.414 0 0 1 0-2l2-2a1.414 1.414 0 0 1 2 0zm-4 14h8m-6-8l-8 8a2.121 2.121 0 1 1-3-3l8-8");
}

</style>
