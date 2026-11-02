<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sggkhmbre"/><path class="uhfpy1bub"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:currency-solana-duocolor" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sggkhmbre {
  stroke-opacity: 0.4;
  d: path("m4 10l4 4m8-4l4 4");
}

.uhfpy1bub {
  d: path("M8 6h12l-4 4H4zm0 8h12l-4 4H4z");
}

</style>
