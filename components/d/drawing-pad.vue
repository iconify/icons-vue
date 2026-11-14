<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h8rqt3b1h"/><path class="o4b971bzq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:drawing-pad" /></template>
<style>
.h8rqt3b1h {
  d: path("M8.5 4.5h7A3.5 3.5 0 0 1 19 8v10a3.5 3.5 0 0 1-3.5 3.5h-7A3.5 3.5 0 0 1 5 18V8a3.5 3.5 0 0 1 3.5-3.5m0-2v4m3.5-4v4m3.5-4v4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o4b971bzq {
  d: path("m8.75 15.375l.386-1.062a1.5 1.5 0 0 1 .349-.548L13.56 9.69a1.243 1.243 0 0 1 1.815.06a1.455 1.455 0 0 1-.041 1.962l-3.784 3.973a1.5 1.5 0 0 1-.722.421l-1.159.289a.778.778 0 0 1-.919-1.02M9.25 14l2 2");
}

</style>
