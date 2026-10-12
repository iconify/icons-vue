<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="owvim6bvs"/><rect class="z595ebbvw"/><path class="md5itublp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lunar-flag" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.md5itublp {
  d: path("M2.75 21.25C5.25 19.5 8.25 19 12 19s6.75.5 9.25 2.25");
}

.owvim6bvs {
  d: path("M6.5 2.75v16.5");
}

.z595ebbvw {
  width: 12.5px;
  height: 7.5px;
  x: 8.75px;
  y: 3px;
  rx: 1px;
}

</style>
