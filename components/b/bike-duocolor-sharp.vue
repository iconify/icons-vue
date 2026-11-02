<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rsirlo2lt"/><path class="eyyts0bbv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bike-duocolor-sharp" /></template>
<style>
.eyyts0bbv {
  d: path("M2 17a4 4 0 1 1 8 0m0 0a4 4 0 1 1-8 0m12 0a4 4 0 1 1 8 0m0 0a4 4 0 1 1-8 0m-8 0L9 5M8 9h8m2 8L15 5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rsirlo2lt {
  stroke-opacity: 0.4;
  d: path("M6 5h4m5 0h3a2 2 0 0 1 2 2");
}

</style>
