<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="h18ufpzwr"/><rect class="ltdwog57l"/><path class="igiz4vbdc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:coolant-level" /></template>
<style>
.h18ufpzwr {
  width: 6px;
  height: 3px;
  x: 9px;
  y: 2.75px;
  rx: 1px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.igiz4vbdc {
  d: path("M7.5 14.5c1.5-1 3 1 4.5 0s3 1 4.5 0V18a.75.75 0 0 1-.75.75h-7.5A.75.75 0 0 1 7.5 18Z");
}

.ltdwog57l {
  width: 15px;
  height: 15.5px;
  x: 4.5px;
  y: 5.75px;
  rx: 2.5px;
}

</style>
