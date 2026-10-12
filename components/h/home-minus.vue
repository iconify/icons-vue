<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<mask id="SVGsZ1vtcCp" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="jf0axzbmx"/></mask><g class="t_2lkqbxb"><g mask="url(#SVGsZ1vtcCp)"><path class="cqhvd3bst"/></g><path class="fzh0ky66v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:home-minus" /></template>
<style>
.cqhvd3bst {
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 9.75L12 3.25l8.25 6.5v8.5a2 2 0 0 1-2 2H5.75a2 2 0 0 1-2-2Z");
}

.fzh0ky66v {
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.75 17.5h5.5");
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

.t_2lkqbxb {
  fill: none;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
