<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zor-27dll"/><path class="eq9yi4b5o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:binoculars-duocolor-sharp" /></template>
<style>
.eq9yi4b5o {
  d: path("M3 16a3 3 0 1 0 6 0a3 3 0 0 0-6 0m12 0a3 3 0 1 0 6 0a3 3 0 0 0-6 0m-6-5h6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zor-27dll {
  stroke-opacity: 0.4;
  d: path("M3 16c0-3 4-6 4-8V6h2v10m12 0c0-3-4-6-4-8V6h-2v10");
}

</style>
