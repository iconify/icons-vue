<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="xk-oyj3fb"/><path class="ayo2gghbq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:direct-debit" /></template>
<style>
.ayo2gghbq {
  d: path("M2.75 6.75h14m-8.5 8.75a3.5 3.5 0 0 0 3.5 3.5h9m-2.25-2.25L20.75 19l-2.25 2.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xk-oyj3fb {
  width: 14px;
  height: 10.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 2px;
}

</style>
