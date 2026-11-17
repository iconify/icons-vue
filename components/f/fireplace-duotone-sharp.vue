<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="o9fv1zy9s"/><path class="k7j-_qbam"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fireplace-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.k7j-_qbam {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3h18M5 3v18M19 3v18M3 21h18M12 6.5c.313 1.563 1.25 2.813 2.5 3.75c.938.938 1.25 2.188 1.25 3.75a3.75 3.75 0 1 1-7.5 0c0-.937.313-1.562.625-1.875m0 0a1.25 1.25 0 1 0 2.5 0c0-.937-.312-1.25-.625-1.875C10.125 9 10.438 7.75 12 6.5");
}

.o9fv1zy9s {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12 6.5c.311 1.55 1.252 2.813 2.5 3.75c1.008 1.009 1.25 2.376 1.25 3.75a3.75 3.75 0 0 1-7.5 0c0-.639.156-1.405.625-1.875a1.25 1.25 0 0 0 2.5 0c0-.937-.312-1.25-.625-1.875c-.765-1.533.035-2.777 1.25-3.75");
}

</style>
