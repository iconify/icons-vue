<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qyqf4qbqp"/><rect class="fdilnhb6a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:magazine-holder" /></template>
<style>
.fdilnhb6a {
  width: 7.5px;
  height: 4px;
  x: 8.25px;
  y: 14.25px;
  rx: 1px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qyqf4qbqp {
  d: path("M4.75 19.75v-6.5q0-1.5 1.06-2.56l6.88-6.88q1.06-1.06 2.56-1.06h2.5q1.5 0 1.5 1.5v15.5q0 1.5-1.5 1.5H6.25q-1.5 0-1.5-1.5");
}

</style>
