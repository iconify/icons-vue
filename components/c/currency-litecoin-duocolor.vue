<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dghz08b8n"/><path class="bbjcmfb_h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:currency-litecoin-duocolor" /></template>
<style>
.bbjcmfb_h {
  d: path("M9 5v14h10");
}

.dghz08b8n {
  stroke-opacity: 0.4;
  d: path("m5 15l4-2m0 0l4-2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
