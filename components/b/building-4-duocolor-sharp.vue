<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r2ln9-bjf"/><path class="h5r3fvz4z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:building-4-duocolor-sharp" /></template>
<style>
.h5r3fvz4z {
  d: path("M3 20h18M5 20V4h10v16m0-11h4v11");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r2ln9-bjf {
  stroke-opacity: 0.4;
  d: path("M9 8h2m-2 4h2");
}

</style>
