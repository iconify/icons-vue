<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oi7oy-bjw"/><path class="r2p7ctnsr"/><path class="q2f8uxbsq"/><path class="nhzu1577c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:fork-knife-line-duotone" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nhzu1577c {
  d: path("M8.15039 2.41028V8.25528");
}

.oi7oy-bjw {
  d: path("M17.2004 21.9493C16.1004 21.9493 15.8504 21.1143 15.9004 19.9453L16.0004 13.7663C16.0504 13.0148 15.0504 12.7643 14.5504 11.5953C13.9504 9.84181 14.5504 5.75031 16.9504 2.41031C17.4504 1.74231 18.5004 1.99281 18.5004 3.24531V19.9453C18.5004 21.1143 18.2004 21.9493 17.2004 21.9493Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.q2f8uxbsq {
  d: path("M5.5 7.58728C6.75 8.47798 9.55 8.47798 10.8 7.58728");
}

.r2p7ctnsr {
  d: path("M5.5 2.41028V7.58728C5.5 9.50778 7.05 10.5933 7.05 11.9293L6.8 20.1123C6.75 21.2813 7.35 21.9493 8.15 21.9493C8.95 21.9493 9.55 21.2813 9.5 20.1123L9.25 11.9293C9.25 10.5933 10.8 9.50778 10.8 7.58728V2.41028");
}

</style>
