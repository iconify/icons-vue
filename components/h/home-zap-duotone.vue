<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wtkn5k6he"/><path class="jq06h-6vm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:home-zap-duotone" /></template>
<style>
.jq06h-6vm {
  d: path("M9 22L9 15L15 15L15 22M20 2L17 5L21 5L18 8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wtkn5k6he {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 12L22 20C21.9999 21.6568 20.6568 23 19 23L5 23C3.34318 23 2.00011 21.6568 2 20L2 11.9268C2.00002 11.0452 2.38775 10.20775 3.06055 9.63773L10.0605 3.70707C11.0406 2.8767 12.4213 2.7737 13.5008 3.398C13.8099 3.5767 14 3.907 14 4.264L14 8C14 9.6569 15.3431 11 17 11L21 11C21.5523 11 22 11.4477 22 12Z");
  stroke: none;
}

</style>
