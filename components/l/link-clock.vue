<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<mask id="SVGsZ1vtcCp" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="jf0axzbmx"/></mask><g class="hntgybcog"><g mask="url(#SVGsZ1vtcCp)"><path class="zs_t-fbul"/></g><circle class="bf9_qabtn"/><path class="f-l8bxkjq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:link-clock" /></template>
<style>
.bf9_qabtn {
  cx: 17.5px;
  cy: 17.5px;
  r: 3.5px;
}

.f-l8bxkjq {
  d: path("M17.5 15.75v1.75l1.25 1");
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

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.zs_t-fbul {
  d: path("M9.25 7.5H7.5a4.5 4.5 0 0 0 0 9h1.75m5.5-9h1.75a4.5 4.5 0 0 1 0 9h-1.75m-6-4.5h6.5");
}

</style>
