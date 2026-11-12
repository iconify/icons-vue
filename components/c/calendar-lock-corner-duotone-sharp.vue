<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="nzgde0fvs"/><path class="kqbiuvo2p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-lock-corner-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.kqbiuvo2p {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 21H4V5h16v4M8 3v2m8-2v2M4 9h16m-7 7h8v5h-8Zm2 0v-1a2 2 0 1 1 4 0v1");
}

.nzgde0fvs {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9 9v12H4V9Z");
}

</style>
