<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mhypmqbih"/><path class="h_cavqskd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:inverter-duocolor-sharp" /></template>
<style>
.h_cavqskd {
  d: path("M4 3h16v18H4Zm5 14h6");
}

.mhypmqbih {
  stroke-opacity: 0.4;
  d: path("M8 11V7h8v4a5 5 0 0 1-8 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
