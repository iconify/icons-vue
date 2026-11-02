<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="l1txs0sri"/><path class="h-ubqc5_h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:golf-duocolor-sharp" /></template>
<style>
.h-ubqc5_h {
  d: path("M10 11V3l8 4zm0 0v6");
}

.l1txs0sri {
  stroke-opacity: 0.4;
  d: path("M6 19c0 1.105 1.79 2 4 2s4-.895 4-2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
