<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<mask id="SVGsZ1vtcCp" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="jf0axzbmx"/></mask><g class="hntgybcog"><g mask="url(#SVGsZ1vtcCp)"><rect class="fqspdobtc"/><rect class="p8f0y4p3y"/><path class="rs_ux8b0z"/></g><path class="beqvkx5mb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:clapperboard-check" /></template>
<style>
.beqvkx5mb {
  d: path("m14.75 17.75l1.75 1.75l3.5-3.75");
}

.fqspdobtc {
  width: 18.5px;
  height: 11.5px;
  x: 2.75px;
  y: 9.75px;
  rx: 2.5px;
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

.p8f0y4p3y {
  width: 18.5px;
  height: 4.25px;
  x: 2.75px;
  y: 3px;
  rx: 1.25px;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.rs_ux8b0z {
  d: path("m8.25 3l-2 4.25m7-4.25l-2 4.25m7-4.25l-2 4.25");
}

</style>
