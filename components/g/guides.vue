<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lnu8_1bht"/><path class="i_96clbee"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:guides" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i_96clbee {
  fill: currentColor;
  d: path("M21.5 7.858v.284a1.307 1.307 0 0 1-2 1.108a1.474 1.474 0 0 1 0-2.5a1.307 1.307 0 0 1 2 1.108M7.858 21.5h.284a1.307 1.307 0 0 0 1.108-2a1.474 1.474 0 0 0-2.5 0a1.307 1.307 0 0 0 1.108 2");
}

.lnu8_1bht {
  d: path("M2.5 8h15M8 2.5v15");
}

</style>
