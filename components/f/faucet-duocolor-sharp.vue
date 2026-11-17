<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ntyri_bie"/><path class="wb38n3bin"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:faucet-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ntyri_bie {
  stroke-opacity: 0.4;
  d: path("M21 19a2 2 0 1 1-4 0c0-1 1-2 2-3c1 1 2 2 2 3");
}

.wb38n3bin {
  d: path("M3 6h18v6h-4v-2H3zm0-2v8m4-9h6m-3 0v3");
}

</style>
