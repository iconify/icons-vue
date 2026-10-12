<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ndpz6rqpf"/><rect class="daejfpnvt"/><path class="cuu-5bbsj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:drill" /></template>
<style>
.cuu-5bbsj {
  d: path("M19 8h2.25M6.5 17.25H10");
}

.daejfpnvt {
  width: 2.5px;
  height: 4.5px;
  x: 16.5px;
  y: 5.75px;
  rx: 0.75px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ndpz6rqpf {
  d: path("M5 4.75h9.5a2 2 0 0 1 2 2v2.5a2 2 0 0 1-2 2h-3.75l.75 8.4a1 1 0 0 1-1 1.1H6.75a1 1 0 0 1-1-1.1l.75-8.4H5A2.25 2.25 0 0 1 2.75 9V7A2.25 2.25 0 0 1 5 4.75");
}

</style>
