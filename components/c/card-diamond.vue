<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ld656tbbe"/><path class="w3s972bbj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:card-diamond" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ld656tbbe {
  width: 14.5px;
  height: 18.5px;
  x: 4.75px;
  y: 2.75px;
  rx: 2.25px;
}

.w3s972bbj {
  d: path("m12.61 7.29l3.03 3.92q.61.79 0 1.58l-3.03 3.92q-.61.79-1.22 0l-3.03-3.92q-.61-.79 0-1.58l3.03-3.92q.61-.79 1.22 0");
}

</style>
