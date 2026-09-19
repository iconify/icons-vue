<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ag-2erb0b"/><path class="jt3zmlbhy"/><circle class="cy7fepedc"/><circle class="hk89etbcy"/><circle class="uoc-kyb4e"/><circle class="xo6liv4pf"/><circle class="vfgedub-y"/><circle class="rd31cbbbe"/><circle class="mn5nf5brk"/><circle class="o8nexr61k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:famistudio" /></template>
<style>
.ag-2erb0b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.167 17.833H42.5v12.333H30.167ZM5.5 17.816h12.333v12.333H5.5Zm12.333 12.351h12.333V42.5H17.833Zm0-24.667h12.333v12.333H17.833Z");
}

.cy7fepedc {
  cx: 32.743px;
  cy: 20.43px;
  r: 0.75px;
  fill: currentColor;
}

.hk89etbcy {
  cx: 37.529px;
  cy: 20.43px;
  r: 0.75px;
  fill: currentColor;
}

.jt3zmlbhy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.723 8.39h6.553v6.553h-6.553zm-9.056 12.149l3.688 6.888H7.979zm11.141 12.156v7.277m-2.404-6.075v4.873m4.809-4.288v3.702m2.404-2.553v1.405");
}

.mn5nf5brk {
  cx: 35.136px;
  cy: 27.57px;
  r: 0.75px;
  fill: currentColor;
}

.o8nexr61k {
  cx: 39.923px;
  cy: 27.57px;
  r: 0.75px;
  fill: currentColor;
}

.rd31cbbbe {
  cx: 39.923px;
  cy: 22.832px;
  r: 0.75px;
  fill: currentColor;
}

.uoc-kyb4e {
  cx: 32.743px;
  cy: 25.191px;
  r: 0.75px;
  fill: currentColor;
}

.vfgedub-y {
  cx: 35.136px;
  cy: 22.832px;
  r: 0.75px;
  fill: currentColor;
}

.xo6liv4pf {
  cx: 37.529px;
  cy: 25.191px;
  r: 0.75px;
  fill: currentColor;
}

</style>
