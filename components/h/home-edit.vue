<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<mask id="SVGsZ1vtcCp" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="jf0axzbmx"/></mask><g class="t_2lkqbxb"><g mask="url(#SVGsZ1vtcCp)"><path class="cqhvd3bst"/></g><path class="rpcix8but"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:home-edit" /></template>
<style>
.cqhvd3bst {
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 9.75L12 3.25l8.25 6.5v8.5a2 2 0 0 1-2 2H5.75a2 2 0 0 1-2-2Z");
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

.rpcix8but {
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m15.25 19.75l.5-2.25l2.5-2.5A1.24 1.24 0 0 1 20 16.75l-2.5 2.5Zm1-2.75L18 18.75");
}

.t_2lkqbxb {
  fill: none;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
