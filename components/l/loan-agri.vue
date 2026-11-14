<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y7a7494hf"/><path class="nr2kwkbiv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:loan-agri" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nr2kwkbiv {
  d: path("M17 15h2a3 3 0 0 1 0 6h-2");
}

.y7a7494hf {
  d: path("M10 21.5v-15m0-2c-1-1-1-2 0-2.5c1 .5 1 1.5 0 2.5m0 5C8 9.5 6.5 8 6.25 6c2 0 3.5 1.5 3.75 3.5m0 0c2 0 3.5-1.5 3.75-3.5c-2 0-3.5 1.5-3.75 3.5m0 4.5c-2 0-3.5-1.5-3.75-3.5c2 0 3.5 1.5 3.75 3.5m0 0c2 0 3.5-1.5 3.75-3.5c-2 0-3.5 1.5-3.75 3.5m0 4.5c-2 0-3.5-1.5-3.75-3.5c2 0 3.5 1.5 3.75 3.5m4-.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

</style>
