<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="m-o1ggpmj"/><path class="wrqzp2bze"/><path class="g-1-t1bbf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:excavator" /></template>
<style>
.g-1-t1bbf {
  d: path("M17.5 10.25h3.75V12a2.75 2.75 0 0 1-2.75 2.75h-1Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m-o1ggpmj {
  width: 12.5px;
  height: 4.5px;
  x: 2.75px;
  y: 16.75px;
  rx: 2.25px;
}

.wrqzp2bze {
  d: path("M5.5 19h7m-8.75-2.25v-7a1.5 1.5 0 0 1 1.5-1.5h3.6a1.5 1.5 0 0 1 1.3.75l2.6 4.5v3.25Zm0 0h9M6 11.25h3m3.75 1.5l3.75-7.5l3.75 5");
}

</style>
