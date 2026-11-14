<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y0kcg3bsw"/><path class="fq_k6j7mb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:face-blow-kiss" /></template>
<style>
.fq_k6j7mb {
  d: path("M10.5 15q2 .75 0 1.5q2 .75 0 1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y0kcg3bsw {
  d: path("M2.25 13.75a7.75 7.75 0 1 0 15.5 0a7.75 7.75 0 1 0-15.5 0M18.75 8L16 5.25A1.8 1.8 0 0 1 18.75 3a1.8 1.8 0 0 1 2.75 2.25ZM6.5 11.5h2m3 0h2");
}

</style>
