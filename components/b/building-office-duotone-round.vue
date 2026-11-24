<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="pnk-9qhqp"/><path class="e1abd6jzx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:building-office-duotone-round" /></template>
<style>
.e1abd6jzx {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 21V9a4 4 0 0 1 4-4h8a4 4 0 0 1 4 4v12M3 21h18M8 9v4m4-4v4m4-4v4m-6 8v-2a2 2 0 1 1 4 0v2");
}

.ft5dv1b6b {
  fill: none;
}

.pnk-9qhqp {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 21V9a4 4 0 0 1 4-4h8a4 4 0 0 1 4 4v12Z");
}

</style>
