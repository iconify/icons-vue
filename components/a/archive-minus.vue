<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<mask id="SVGsZ1vtcCp" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="jf0axzbmx"/></mask><g class="hntgybcog"><g mask="url(#SVGsZ1vtcCp)"><rect class="hhdoz-_gs"/><path class="ntnd4actw"/></g><path class="notrppkqh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:archive-minus" /></template>
<style>
.hhdoz-_gs {
  width: 18.5px;
  height: 5px;
  x: 2.75px;
  y: 3.75px;
  rx: 1.5px;
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

.notrppkqh {
  d: path("M14.75 17.5h5.5");
}

.ntnd4actw {
  d: path("M4.25 8.75h15.5v9a2.5 2.5 0 0 1-2.5 2.5H6.75a2.5 2.5 0 0 1-2.5-2.5Zm5.75 4h4");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
