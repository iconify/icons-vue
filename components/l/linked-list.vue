<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="jpbmcvb4y"/><rect class="l0j9kwb6c"/><path class="t17jwqs_z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:linked-list" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jpbmcvb4y {
  width: 7.5px;
  height: 6.5px;
  x: 2.75px;
  y: 3.75px;
  rx: 1.75px;
}

.l0j9kwb6c {
  width: 7.5px;
  height: 6.5px;
  x: 13.75px;
  y: 13.75px;
  rx: 1.75px;
}

.t17jwqs_z {
  d: path("M10.25 7H15a2.5 2.5 0 0 1 2.5 2.5v2.75m-2-2l2 2l2-2M13.75 17h-4.5m0-2.25v4.5");
}

</style>
