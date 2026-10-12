<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cuimd9b-p"/><rect class="kmv2ism-o"/><rect class="alp_--1gp"/><rect class="a0jajxbxq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gantt-bars" /></template>
<style>
.a0jajxbxq {
  width: 8px;
  height: 3.5px;
  x: 13.25px;
  y: 16.75px;
  rx: 1.75px;
}

.alp_--1gp {
  width: 9px;
  height: 3.5px;
  x: 9.5px;
  y: 10.25px;
  rx: 1.75px;
}

.cuimd9b-p {
  d: path("M2.75 2.75v18.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kmv2ism-o {
  width: 8px;
  height: 3.5px;
  x: 5.5px;
  y: 3.75px;
  rx: 1.75px;
}

</style>
