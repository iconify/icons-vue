<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<mask id="SVGsZ1vtcCp" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="jf0axzbmx"/></mask><g class="hntgybcog"><g mask="url(#SVGsZ1vtcCp)"><path class="l61j1qbza"/><circle class="fpq61538s"/></g><rect class="ecwkvnb4e"/><path class="qxk6h6bbi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cart-lock" /></template>
<style>
.ecwkvnb4e {
  width: 5.5px;
  height: 4px;
  x: 14.75px;
  y: 17px;
  rx: 1px;
}

.fpq61538s {
  cx: 9.25px;
  cy: 18.75px;
  r: 1.5px;
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

.l61j1qbza {
  d: path("M2.75 3.75h1.4A1.5 1.5 0 0 1 5.61 4.9L7.65 14m-1.7-7.75H19.5a1 1 0 0 1 .97 1.24l-1.2 4.8A2 2 0 0 1 17.33 14H7.65Z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qxk6h6bbi {
  d: path("M16 17v-1a1.5 1.5 0 0 1 3 0v1");
}

</style>
