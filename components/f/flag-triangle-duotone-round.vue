<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="w1ijhpkyi"/><path class="hhcglbbdd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flag-triangle-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hhcglbbdd {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 15V7c0-1.838 2.162-2.919 4-2l4 2c1.648.824 1.648 3.176 0 4zm0 0v6");
}

.w1ijhpkyi {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5 7c0-.633.184-1.247.536-1.774a3.44 3.44 0 0 1 1.328-1.154c1.126-.563 2.463-.526 3.583.034l4 2a3.234 3.234 0 0 1 0 5.788l-8 4A1 1 0 0 1 5 15Z");
}

</style>
