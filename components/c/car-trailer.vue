<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="s1qubm6cb"/><path class="x5mr4b4bl"/><circle class="n68tfnh1s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:car-trailer" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n68tfnh1s {
  cx: 9.25px;
  cy: 17.75px;
  r: 2.75px;
}

.s1qubm6cb {
  width: 13px;
  height: 9px;
  x: 2.75px;
  y: 8.75px;
  rx: 1.5px;
}

.x5mr4b4bl {
  d: path("M2.75 11.75h13m0 2.5h5.5m-2 0v4m-1 0h2");
}

</style>
