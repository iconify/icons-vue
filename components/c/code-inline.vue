<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="a1p0_acds"/><path class="xc8hoccpi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:code-inline" /></template>
<style>
.a1p0_acds {
  width: 18.5px;
  height: 11.5px;
  x: 2.75px;
  y: 6.25px;
  rx: 5.75px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xc8hoccpi {
  d: path("M9 9.5L6.75 12L9 14.5m6-5l2.25 2.5L15 14.5M11.25 12h1.5");
}

</style>
