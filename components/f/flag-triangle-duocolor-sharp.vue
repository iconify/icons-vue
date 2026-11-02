<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="m1_xilbul"/><path class="s5c46mbxl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flag-triangle-duocolor-sharp" /></template>
<style>
.m1_xilbul {
  stroke-opacity: 0.4;
  d: path("M6 15v6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s5c46mbxl {
  d: path("M6 15V3l12 6z");
}

</style>
