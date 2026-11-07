<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mxb29u3id"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:import-round" /></template>
<style>
.mxb29u3id {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 7a2 2 0 0 0-2 2v8a4 4 0 0 0 4 4h10a4 4 0 0 0 4-4V9a2 2 0 0 0-2-2M9 12l3 3l3-3m-3 3V3");
}

</style>
