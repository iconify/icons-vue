<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f4tm4cbsj"/><path class="agtqf7biq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lighting-shop" /></template>
<style>
.agtqf7biq {
  d: path("M10.5 18.75V17a3.5 3.5 0 1 1 3 0v1.75Z");
}

.f4tm4cbsj {
  d: path("m3.658 5.026l.5-1.5A1.5 1.5 0 0 1 5.581 2.5h12.838a1.5 1.5 0 0 1 1.423 1.026l.5 1.5A1.5 1.5 0 0 1 18.919 7H5.081a1.5 1.5 0 0 1-1.423-1.974M4.5 7v14.5h15V7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
