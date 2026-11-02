<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="slqbdqt9w"/><path class="cesmxqb_w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:invoice-duocolor-sharp" /></template>
<style>
.cesmxqb_w {
  d: path("M13 3H5v18h14V9m-6-6l6 6m-6-6v6h6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.slqbdqt9w {
  stroke-opacity: 0.4;
  d: path("M9 7h1m-1 6h6m-3 4h3");
}

</style>
