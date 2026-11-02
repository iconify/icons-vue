<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tbicm0btt"/><path class="kgjbb4tdg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:eye-off-duocolor-sharp" /></template>
<style>
.kgjbb4tdg {
  d: path("M17 17c-1.425.797-3.297 1-5 1a9.75 9.75 0 0 1-9-6c.859-2.061 2.132-3.955 4-5m5-1a9.75 9.75 0 0 1 9 6c-.288.69-.576 1.408-1 2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tbicm0btt {
  stroke-opacity: 0.4;
  d: path("M11 11c-.362.362-1 .448-1 1a2 2 0 0 0 2 2c.552 0 .638-.638 1-1M2 2l20 20");
}

</style>
