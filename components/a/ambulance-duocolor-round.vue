<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wh739bcfn"/><path class="alqpcvbyk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ambulance-duocolor-round" /></template>
<style>
.alqpcvbyk {
  d: path("M5 18a2 2 0 1 0 4 0a2 2 0 0 0-4 0m10 0a2 2 0 1 0 4 0a2 2 0 0 0-4 0m-9-7h4M8 9v4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wh739bcfn {
  stroke-opacity: 0.4;
  d: path("M5 18a2 2 0 0 1-2-2V9a4 4 0 0 1 4-4h3a3 3 0 0 1 3 3v10m0-10h3c.64 0 1.36.36 2 1l2 2c.64.64 1 1.36 1 2v3a2 2 0 0 1-2 2M9 18h6m-2-6h7");
}

</style>
