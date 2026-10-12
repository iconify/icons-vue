<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="imzb2csox"/><path class="yv0gp-35t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:caulk-gun" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.imzb2csox {
  width: 10.5px;
  height: 4.5px;
  x: 7.75px;
  y: 5px;
  rx: 1.5px;
}

.yv0gp-35t {
  d: path("M7.75 6.25L3 7v1l4.75.75m10.5-1.5h3m0-2.5v5m-4.5-.25L18 18.75M14 9.5l-1.25 5.75");
}

</style>
