<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="vnve804ta"/><path class="fqlbixy5a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cooking-pot-duotone" /></template>
<style>
.fqlbixy5a {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 11v7a2 2 0 0 0 2 2h10a2 2 0 0 0 2-2v-7M5 11h14M3 14h2m14 0h2M6 11a6.5 6.5 0 0 1 12 0m-6-4V4m-2 0h4");
}

.ft5dv1b6b {
  fill: none;
}

.vnve804ta {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6 11a6.5 6.5 0 0 1 12 0h1v7a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2v-7Z");
}

</style>
