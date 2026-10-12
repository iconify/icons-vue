<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<mask id="SVGsZ1vtcCp" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="jf0axzbmx"/></mask><g class="hntgybcog"><g mask="url(#SVGsZ1vtcCp)"><rect class="x4hlzsk-k"/><path class="eo9e_77nv"/></g><rect class="ecwkvnb4e"/><path class="qxk6h6bbi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:laptop-lock" /></template>
<style>
.ecwkvnb4e {
  width: 5.5px;
  height: 4px;
  x: 14.75px;
  y: 17px;
  rx: 1px;
}

.eo9e_77nv {
  d: path("M2.75 19h18.5");
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

.qxk6h6bbi {
  d: path("M16 17v-1a1.5 1.5 0 0 1 3 0v1");
}

.x4hlzsk-k {
  width: 15.5px;
  height: 11px;
  x: 4.25px;
  y: 4.25px;
  rx: 2px;
}

</style>
