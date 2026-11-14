<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vu0hr2bnc"/><path class="w344zqb8c"/><path class="oiyll2h9g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:book-cart-library" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oiyll2h9g {
  d: path("M5.5 18a2 2 0 1 0 4 0a2 2 0 1 0-4 0m10 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

.vu0hr2bnc {
  d: path("M2.5 2.5H4V16h17");
}

.w344zqb8c {
  d: path("M8 6.5h1A1.5 1.5 0 0 1 10.5 8v6.5A1.5 1.5 0 0 1 9 16H8a1.5 1.5 0 0 1-1.5-1.5V8A1.5 1.5 0 0 1 8 6.5m9.194-.875l.978.208a1.5 1.5 0 0 1 1.156 1.779l-1.56 7.337a1.5 1.5 0 0 1-1.779 1.155l-.978-.208a1.5 1.5 0 0 1-1.155-1.779l1.559-7.336a1.5 1.5 0 0 1 1.779-1.156");
}

</style>
