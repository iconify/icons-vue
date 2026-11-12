<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="vyosh6ymd"/><path class="au05w3lrq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:git-rebase-duotone-sharp" /></template>
<style>
.au05w3lrq {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 6a2 2 0 1 0 4 0a2 2 0 0 0-4 0m0 12a2 2 0 1 0 4 0a2 2 0 0 0-4 0M17 6a2 2 0 1 0 4 0a2 2 0 0 0-4 0M5 8v8M7 6h10m2 15v-8h-8m3-3l-3 3l3 3");
}

.ft5dv1b6b {
  fill: none;
}

.vyosh6ymd {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M2.236 4.832A3 3 0 1 1 7.763 7.17a3 3 0 0 1-5.527-2.338m14 0a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338m-14 12a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338");
}

</style>
