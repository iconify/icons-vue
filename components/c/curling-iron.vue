<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="vfi-r0bvw"/><path class="z_5734k-s"/><rect class="gsdja4bbk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:curling-iron" /></template>
<style>
.gsdja4bbk {
  width: 4.5px;
  height: 6.25px;
  x: 9.75px;
  y: 15px;
  rx: 1.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vfi-r0bvw {
  width: 4.5px;
  height: 10px;
  x: 9.75px;
  y: 2.75px;
  rx: 2.25px;
}

.z_5734k-s {
  d: path("m9.75 6l4.5-1.5m-4.5 5l4.5-1.5M5.71 4.46l.58-.17q.96-.29.96.71v7.25q0 1-.96.71l-.58-.17q-.96-.29-.96-1.29V5.75q0-1 .96-1.29");
}

</style>
