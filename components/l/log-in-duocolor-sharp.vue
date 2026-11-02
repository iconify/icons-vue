<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="slkd4ybpr"/><path class="nka2zfbyg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:log-in-duocolor-sharp" /></template>
<style>
.nka2zfbyg {
  d: path("M8 7V3h11v18H8v-4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.slkd4ybpr {
  stroke-opacity: 0.4;
  d: path("m12 15l3-3m0 0l-3-3m3 3H5");
}

</style>
