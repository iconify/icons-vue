<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<mask id="SVGsZ1vtcCp" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="jf0axzbmx"/></mask><g class="hntgybcog"><g mask="url(#SVGsZ1vtcCp)"><path class="kmeqglalm"/><rect class="s8e5_8bzb"/></g><path class="uaginbcio"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:clipboard-edit" /></template>
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

.kmeqglalm {
  d: path("M8.75 4.25h-1.5a2.5 2.5 0 0 0-2.5 2.5v12a2.5 2.5 0 0 0 2.5 2.5h9.5a2.5 2.5 0 0 0 2.5-2.5v-12a2.5 2.5 0 0 0-2.5-2.5h-1.5");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.s8e5_8bzb {
  width: 6.5px;
  height: 3.5px;
  x: 8.75px;
  y: 2.75px;
  rx: 1.25px;
}

.uaginbcio {
  d: path("m15.25 19.75l.5-2.25l2.5-2.5A1.24 1.24 0 0 1 20 16.75l-2.5 2.5Zm1-2.75L18 18.75");
}

</style>
