<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="m48cb1y7y"/><path class="ns8txxbxy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-off-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.m48cb1y7y {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7.354 3.354A4 4 0 0 1 9 3h4l6 6v6Zm10.474 16.474A3.97 3.97 0 0 1 15 21H9a4 4 0 0 1-4-4V7Z");
}

.ns8txxbxy {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 3H9c-.587 0-1.144.126-1.646.353M5 7v10a4 4 0 0 0 4 4h6a4 4 0 0 0 2.828-1.172M19 15V9m-6-6l6 6m-6-6v4a2 2 0 0 0 2 2h4M2 4l18 18");
}

</style>
