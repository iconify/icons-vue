<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bcbpfubhp"/><path class="uo1ulhbxa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hieroglyph-panel" /></template>
<style>
.bcbpfubhp {
  d: path("M4.5 21.5V10a7.5 7.5 0 0 1 15 0v11.5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uo1ulhbxa {
  d: path("M7.5 9.5q4.5-5.5 9 0q-4.5 5.5-9 0m4.5 0h.01M7.5 17.25q1.5-2 3 0t3 0t3 0");
}

</style>
