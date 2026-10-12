<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ez8p-cc0k"/><path class="tbvbossga"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:file-cabinet-open" /></template>
<style>
.ez8p-cc0k {
  width: 18.5px;
  height: 9px;
  x: 2.75px;
  y: 12.25px;
  rx: 2px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tbvbossga {
  d: path("M9.5 16.75h5M5.5 10V4.25A1.5 1.5 0 0 1 7 2.75h3.25l1.5 1.75H17A1.5 1.5 0 0 1 18.5 6v4");
}

</style>
