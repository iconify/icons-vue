<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="on-u7sbwk"/><path class="mexb97g3p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-edit-corner-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mexb97g3p {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 21H8a4 4 0 0 1-4-4V9a4 4 0 0 1 4-4h8a4 4 0 0 1 4 4M8 3v2m8-2v2M4 9h16m-7 12v-3l5-5l3 3l-5 5Z");
}

.on-u7sbwk {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M13 9a4 4 0 0 0-4 4v8H8a4 4 0 0 1-4-4V9Zm0 9l5-5l3 3l-5 5h-3Z");
}

</style>
