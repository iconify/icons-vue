<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f15wrccqb"/><path class="mhxa_5fhj"/><path class="ytoduqagm"/><path class="fx2afhbrd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:battery-rechargeable" /></template>
<style>
.f15wrccqb {
  d: path("M6.875 7h7.75A4.375 4.375 0 0 1 19 11.375v1.25A4.375 4.375 0 0 1 14.625 17h-7.75A4.375 4.375 0 0 1 2.5 12.625v-1.25A4.375 4.375 0 0 1 6.875 7M21.5 10.5v3");
}

.fx2afhbrd {
  d: path("m10.25 14.25l-1.75-1v2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mhxa_5fhj {
  d: path("M8.585 10.75a2.5 2.5 0 0 1 4.33 0");
}

.ytoduqagm {
  d: path("m11.25 9.75l1.75 1v-2m-.085 4.5a2.5 2.5 0 0 1-4.33 0");
}

</style>
