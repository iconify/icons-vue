<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dhdewibyh"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:legends-of-runterra" /></template>
<style>
.dhdewibyh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.588 31.914V12.5h4.67c2.639 0 4.78 2.145 4.78 4.79s-2.14 4.79-4.78 4.79h-4.67m4.669 0l4.669 9.831m-1.886 0h2.745m-11.57 0h2.745M18.215 12.5h1.373m-5.489 23.283h6.668L24 37.5l3.234-1.717h6.667");
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
