<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<mask id="SVGsZ1vtcCp" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="jf0axzbmx"/></mask><g class="hntgybcog"><g mask="url(#SVGsZ1vtcCp)"><rect class="xqkiicbwe"/><path class="msb4-ibai"/></g><path class="f35xrjbjk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:headphones-x" /></template>
<style>
.f35xrjbjk {
  d: path("m15.25 15.25l4.5 4.5m0-4.5l-4.5 4.5");
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

.msb4-ibai {
  d: path("M3.75 14.25V12a8.25 8.25 0 0 1 16.5 0v2.25");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.xqkiicbwe {
  width: 4.5px;
  height: 7px;
  x: 3.75px;
  y: 13.25px;
  rx: 2px;
}

</style>
