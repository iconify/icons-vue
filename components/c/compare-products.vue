<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="fepl4ybjy"/><path class="jm7ytx8vq"/><rect class="mugr19b-p"/><path class="uf23bpmyf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:compare-products" /></template>
<style>
.fepl4ybjy {
  width: 7.5px;
  height: 12.75px;
  x: 2.75px;
  y: 2.75px;
  rx: 1.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jm7ytx8vq {
  d: path("M5 6.5h3m-3 3h3");
}

.mugr19b-p {
  width: 7.5px;
  height: 12.75px;
  x: 13.75px;
  y: 2.75px;
  rx: 1.5px;
}

.uf23bpmyf {
  d: path("M16 6.5h3m-3 3h3M5.25 19.25h13.5M7.25 17.5l-2 1.75l2 1.75m9.5-3.5l2 1.75l-2 1.75");
}

</style>
