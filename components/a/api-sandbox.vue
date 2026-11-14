<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cw9kw7brk"/><path class="ys15868pa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:api-sandbox" /></template>
<style>
.cw9kw7brk {
  d: path("M3 12v6.5A2.5 2.5 0 0 0 5.5 21h13a2.5 2.5 0 0 0 2.5-2.5V12m-5.271-8.376l2.867 2.007m-1.434-1.003l-5.449 7.782");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ys15868pa {
  d: path("m11.099 11.979l1.229.861a1.75 1.75 0 0 1 .429 2.437l-1.161 1.659a1.75 1.75 0 0 1-1.13.72l-1.044.184a1.75 1.75 0 0 1-2.028-1.42l-.184-1.044a1.75 1.75 0 0 1 .29-1.308l1.162-1.659a1.75 1.75 0 0 1 2.437-.43");
}

</style>
