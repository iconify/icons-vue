<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="hhdoz-_gs"/><path class="ntnd4actw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:archive-restore" /></template>
<style>
.hhdoz-_gs {
  width: 18.5px;
  height: 5px;
  x: 2.75px;
  y: 3.75px;
  rx: 1.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ntnd4actw {
  d: path("M4.25 8.75h15.5v9a2.5 2.5 0 0 1-2.5 2.5H6.75a2.5 2.5 0 0 1-2.5-2.5Zm5.75 4h4");
}

</style>
