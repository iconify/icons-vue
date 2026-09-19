<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="au3ci6uef"/><circle class="n_d664s1d"/><path class="byn14r31k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dirk" /></template>
<style>
.au3ci6uef {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.012 25.382a2.987 2.987 0 0 1 2.987-2.988h0m-2.987.001v7.915m5.514-11.948V30.31m.001-2.538l5.408-5.382m-3.687 3.669l4.252 4.233");
}

.byn14r31k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.214 22.395v7.915m-10.714 0V18.362h2.688a5.227 5.227 0 0 1 5.227 5.227v1.494a5.227 5.227 0 0 1-5.227 5.227z");
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.n_d664s1d {
  cx: 22.214px;
  cy: 18.735px;
  r: 0.75px;
  fill: currentColor;
}

</style>
