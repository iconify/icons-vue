<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qo8f3buxs"/><rect class="qyepnrbgy"/><path class="yi9nivb2c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:heading-3" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qo8f3buxs {
  d: path("M3 4.75v14.5m5.75-14.5v14.5M3 12h5.75");
}

.qyepnrbgy {
  width: 9.5px;
  height: 12px;
  x: 11.75px;
  y: 7.25px;
  rx: 2.5px;
}

.yi9nivb2c {
  d: path("M14.75 10h3.5l-2 2.5a2.1 2.1 0 1 1-1.75 3.4");
}

</style>
