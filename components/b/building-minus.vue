<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<mask id="SVGsZ1vtcCp" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="jf0axzbmx"/></mask><g class="y9tr6bcfx"><g mask="url(#SVGsZ1vtcCp)"><rect class="f8hk9kbgp"/><path class="iaxds5n-q"/></g><path class="rsg8-qblp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:building-minus" /></template>
<style>
.f8hk9kbgp {
  width: 13.5px;
  height: 18.5px;
  x: 5.25px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

.iaxds5n-q {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 6.75h.01m5.99 0h.01M9 10.25h.01m5.99 0h.01M9 13.75h.01");
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

.rsg8-qblp {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.75 17.5h5.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
