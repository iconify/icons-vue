<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="c0nl5isdz"/><path class="akp9ikbed"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cast-duocolor-sharp" /></template>
<style>
.akp9ikbed {
  d: path("M3 7V5h18v14h-6");
}

.c0nl5isdz {
  stroke-opacity: 0.4;
  d: path("M3 11a8 8 0 0 1 8 8m-8-4a4 4 0 0 1 4 4m-4 0h.01");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
