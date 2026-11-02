<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="h8ly_dbnf"/><path class="o8tz0l51y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:git-fork-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.h8ly_dbnf {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M2.236 4.832A3 3 0 1 1 7.763 7.17a3 3 0 0 1-5.527-2.338m14 0a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338m-7 12a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338");
}

.o8tz0l51y {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 6a2 2 0 1 0 4 0a2 2 0 0 0-4 0m14 0a2 2 0 1 0 4 0a2 2 0 0 0-4 0m-7 12a2 2 0 1 0 4 0a2 2 0 0 0-4 0m2-6v4M5 8v4h14V8");
}

</style>
