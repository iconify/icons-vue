<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="s1sbiaces"/><rect class="lrb3wnbfw"/><rect class="aydh7op0y"/><path class="uaz3xbczv"/><circle class="z6httfbqu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:federated-learning" /></template>
<style>
.aydh7op0y {
  width: 5px;
  height: 5px;
  x: 9.5px;
  y: 16.25px;
  rx: 1.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lrb3wnbfw {
  width: 5px;
  height: 5px;
  x: 16.25px;
  y: 2.75px;
  rx: 1.25px;
}

.s1sbiaces {
  width: 5px;
  height: 5px;
  x: 2.75px;
  y: 2.75px;
  rx: 1.25px;
}

.uaz3xbczv {
  d: path("m7.75 7.75l1.8 1.27m6.7-1.27l-1.8 1.27M12 13.75v2.5");
}

.z6httfbqu {
  cx: 12px;
  cy: 10.75px;
  r: 3px;
}

</style>
