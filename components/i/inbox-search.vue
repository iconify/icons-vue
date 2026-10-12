<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<mask id="SVGsZ1vtcCp" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="jf0axzbmx"/></mask><g class="hntgybcog"><g mask="url(#SVGsZ1vtcCp)"><path class="z3cxn1bbu"/><path class="vn1l890vq"/></g><path class="zayiqabyy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:inbox-search" /></template>
<style>
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

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.vn1l890vq {
  d: path("M2.75 13.25h4.4l1.1 2.2c.25.5.75.8 1.3.8h4.9c.55 0 1.05-.3 1.3-.8l1.1-2.2h4.4");
}

.z3cxn1bbu {
  d: path("m2.75 13.25l2.6-7.4a2.5 2.5 0 0 1 2.36-1.6h8.58a2.5 2.5 0 0 1 2.36 1.6l2.6 7.4v4.5a2.5 2.5 0 0 1-2.5 2.5H5.25a2.5 2.5 0 0 1-2.5-2.5Z");
}

.zayiqabyy {
  d: path("M14.25 16.75a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m4.5 2L20 20");
}

</style>
