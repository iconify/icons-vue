<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="jztumnbos"/><rect class="w3b_izenq"/><path class="ge9ccosjs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hair-dryer" /></template>
<style>
.ge9ccosjs {
  d: path("M8.75 8.25a1.75 1.75 0 1 1-3.5 0a1.75 1.75 0 1 1 3.5 0m-1 7h2.5q1.25 0 1.04 1.23l-.58 3.54q-.21 1.23-1.46 1.23h-1.5Q6.5 21.25 6.5 20v-3.5q0-1.25 1.25-1.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jztumnbos {
  width: 12.5px;
  height: 8px;
  x: 2.75px;
  y: 4.25px;
  rx: 4px;
}

.w3b_izenq {
  width: 3px;
  height: 5px;
  x: 18.25px;
  y: 5.75px;
  rx: 1px;
}

</style>
