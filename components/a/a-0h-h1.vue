<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><path id="arcticonsA0hH10" class="rh-pfu9-d"/><path id="arcticonsA0hH11" class="a-5x1-gwl"/></defs><rect class="v1i_cobsc"/><use href="#arcticonsA0hH10" class="c-zrgpb5l"/><rect class="bvjlqiy-e"/><use href="#arcticonsA0hH11" class="c-zrgpb5l"/><rect class="v1i_cobsc"/><use href="#arcticonsA0hH10" class="c-zrgpb5l"/><rect class="bvjlqiy-e"/><use href="#arcticonsA0hH11" class="c-zrgpb5l"/><rect class="a68dhd6sv"/><path class="dsm-6hb6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:a-0h-h1" /></template>
<style>
.a-5x1-gwl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 19.463H22");
}

.a68dhd6sv {
  width: 16.5px;
  height: 16.5px;
  x: 26px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
}

.bvjlqiy-e {
  width: 16.5px;
  height: 16.5px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
}

.c-zrgpb5l {
  stroke-linecap: round;
  stroke-linejoin: round;
}

.dsm-6hb6m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26 19.463h16.5");
}

.rh-pfu9-d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 39.963H22");
}

.v1i_cobsc {
  width: 16.5px;
  height: 16.5px;
  x: 5.5px;
  y: 26px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
}

</style>
