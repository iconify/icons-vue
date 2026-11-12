<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="zsrhsdxle"/><path class="p-1ec4b3a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:git-merge-conflict-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.p-1ec4b3a {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 6a2 2 0 1 0 4 0a2 2 0 0 0-4 0m0 12a2 2 0 1 0 4 0a2 2 0 0 0-4 0M5 8v8m0-8a4 4 0 0 0 4 4h4m4-2l4 4m0-4l-4 4");
}

.zsrhsdxle {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M2.236 4.832A3 3 0 1 1 7.763 7.17a3 3 0 0 1-5.527-2.338m0 12a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338");
}

</style>
