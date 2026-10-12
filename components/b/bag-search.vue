<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<mask id="SVGsZ1vtcCp" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="jf0axzbmx"/></mask><g class="hntgybcog"><g mask="url(#SVGsZ1vtcCp)"><path class="o9k8jk4mn"/><path class="dqv2xfb4u"/></g><path class="zayiqabyy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bag-search" /></template>
<style>
.dqv2xfb4u {
  d: path("M8.75 9.75V6.5a3.25 3.25 0 0 1 6.5 0v3.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jf0axzbmx {
  cx: 17.5px;
  cy: 17.5px;
  r: 6px;
}

.o9k8jk4mn {
  d: path("M5.1 8.4a1.75 1.75 0 0 1 1.74-1.65h10.32A1.75 1.75 0 0 1 18.9 8.4l.7 10.3a2.5 2.5 0 0 1-2.5 2.55H6.9a2.5 2.5 0 0 1-2.5-2.55Z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.zayiqabyy {
  d: path("M14.25 16.75a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m4.5 2L20 20");
}

</style>
