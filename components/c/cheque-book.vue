<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jvf382bjc"/><rect class="yfmihlb9h"/><path class="z5iw6ybet"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cheque-book" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jvf382bjc {
  d: path("M4.25 2.75h15.5M3.5 5.25h17");
}

.yfmihlb9h {
  width: 18.5px;
  height: 12.5px;
  x: 2.75px;
  y: 7.75px;
  rx: 2.5px;
}

.z5iw6ybet {
  d: path("M7.25 10.25v1m0 2v1m0 2v1m2.75-5.5h4.5m2 0h1.75M10 16.25h2.5m1.5.5l1.25-2l1.25 2l1.25-2l1.25 2");
}

</style>
