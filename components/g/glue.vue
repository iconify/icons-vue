<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="zk8uc6b_m"/><path class="qcfkstb0t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:glue" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qcfkstb0t {
  d: path("m9.75 10.25l.75-3.5l1.5-4l1.5 4l.75 3.5Zm-.5 5h5.5");
}

.zk8uc6b_m {
  width: 11.5px;
  height: 11px;
  x: 6.25px;
  y: 10.25px;
  rx: 2.5px;
}

</style>
