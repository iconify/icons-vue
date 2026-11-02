<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="m1_xilbul"/><path class="ncqziibma"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flag-triangle-duocolor-round" /></template>
<style>
.m1_xilbul {
  stroke-opacity: 0.4;
  d: path("M6 15v6");
}

.ncqziibma {
  d: path("M6 15V7c0-1.838 2.162-2.919 4-2l4 2c1.648.824 1.648 3.176 0 4z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
