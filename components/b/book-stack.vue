<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="nxjfyhb_k"/><path class="ic330qb6s"/><rect class="au3mjzb6j"/><rect class="vsb483yfn"/><path class="kzpy_zxbw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:book-stack" /></template>
<style>
.au3mjzb6j {
  width: 15px;
  height: 4px;
  x: 5.25px;
  y: 10.5px;
  rx: 1.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ic330qb6s {
  d: path("M6.75 17.25v4");
}

.kzpy_zxbw {
  d: path("M14.25 3.75v4");
}

.nxjfyhb_k {
  width: 18.5px;
  height: 4px;
  x: 2.75px;
  y: 17.25px;
  rx: 1.25px;
}

.vsb483yfn {
  width: 14.5px;
  height: 4px;
  x: 3.75px;
  y: 3.75px;
  rx: 1.25px;
}

</style>
