<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wui7iacqj"/><path class="ezi4ypbgy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fridge-duocolor-sharp" /></template>
<style>
.ezi4ypbgy {
  d: path("M5 3h14v18H5Zm0 7h14");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wui7iacqj {
  stroke-opacity: 0.4;
  d: path("M15 6v1m0 7v3");
}

</style>
