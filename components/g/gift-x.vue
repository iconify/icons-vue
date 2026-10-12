<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<mask id="SVGsZ1vtcCp" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="jf0axzbmx"/></mask><g class="hntgybcog"><g mask="url(#SVGsZ1vtcCp)"><rect class="mbf6vr-el"/><path class="siq_r9b4a"/></g><path class="f35xrjbjk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gift-x" /></template>
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

.mbf6vr-el {
  width: 17.5px;
  height: 4.25px;
  x: 3.25px;
  y: 7.25px;
  rx: 1.25px;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.siq_r9b4a {
  d: path("M4.75 14h14.5v5.25a2 2 0 0 1-2 2H6.75a2 2 0 0 1-2-2ZM12 7.25v14m0-14H8.75a2 2 0 1 1 0-4c1.75 0 2.75 2 3.25 4m0 0h3.25a2 2 0 1 0 0-4c-1.75 0-2.75 2-3.25 4");
}

</style>
