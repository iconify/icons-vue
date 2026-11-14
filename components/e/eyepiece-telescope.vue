<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="riwrv1b8x"/><path class="mya9hsbdc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:eyepiece-telescope" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mya9hsbdc {
  d: path("M15.879 4.719za1.5 1.5 0 0 1 2.049.549l2 3.464a1.5 1.5 0 0 1-.549 2.049a1.5 1.5 0 0 1-2.049-.549l-2-3.464a1.5 1.5 0 0 1 .549-2.049M5.188 13.201l.433-.25a1.5 1.5 0 0 1 2.049.549a1.5 1.5 0 0 1-.549 2.049l-.433.25a1.5 1.5 0 0 1-2.049-.549a1.5 1.5 0 0 1 .549-2.049m8.062.049L10 20.5m3.25-7.25l3.25 7.25");
}

.riwrv1b8x {
  d: path("m7.935 10.46l5.63-3.25a1.75 1.75 0 0 1 2.39.64l.75 1.3a1.75 1.75 0 0 1-.64 2.39l-5.63 3.25a1.75 1.75 0 0 1-2.39-.64l-.75-1.3a1.75 1.75 0 0 1 .64-2.39");
}

</style>
