<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="z0_3bib6e"/><path class="frzyke-5w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:biogas-plant-duocolor-sharp" /></template>
<style>
.frzyke-5w {
  d: path("M3 12v9h12v-9a6.1 6.1 0 0 0-12 0m0 0h12");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.z0_3bib6e {
  stroke-opacity: 0.4;
  d: path("M9.27 7.006A6.1 6.1 0 0 1 21 8m-8.653 0H21m0 0v9h-6");
}

</style>
