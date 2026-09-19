<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e-q8ellht"/><rect transform="rotate(-31.377 18.723 27.874)" class="m_pmdobkn"/><rect transform="rotate(-31.377 31.402 20.452)" class="q0ej2d8ub"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emochi" /></template>
<style>
.e-q8ellht {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m42.5 19.468l-.362-.594c-3.438-5.635-10.792-7.415-16.427-3.977l-9.042 5.511c-5.627 3.438-7.407 10.784-3.977 16.419l3.46 5.673m7.326-7.37l10.719-6.31");
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

.m_pmdobkn {
  width: 3.717px;
  height: 4.679px;
  x: 16.864px;
  y: 25.535px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.859px;
  ry: 1.859px;
}

.q0ej2d8ub {
  width: 3.717px;
  height: 4.679px;
  x: 29.543px;
  y: 18.113px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.859px;
  ry: 1.859px;
}

</style>
