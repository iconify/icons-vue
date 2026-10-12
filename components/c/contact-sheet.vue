<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="lzd_5ob1p"/><path class="kq_pxil3p"/><circle class="boiqtuypj"/><path class="stlv7x7mf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:contact-sheet" /></template>
<style>
.boiqtuypj {
  cx: 15.75px;
  cy: 15.75px;
  r: 3.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kq_pxil3p {
  d: path("M2.75 9.25h13m-6.5-6.5v13");
}

.lzd_5ob1p {
  width: 13px;
  height: 13px;
  x: 2.75px;
  y: 2.75px;
  rx: 2px;
}

.stlv7x7mf {
  d: path("M18.25 18.25L21 21");
}

</style>
