<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d80vtpbwr"/><path class="wwf8subge"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:defibrillator-cabinet" /></template>
<style>
.d80vtpbwr {
  d: path("M7.5 2.5h9A3.5 3.5 0 0 1 20 6v12a3.5 3.5 0 0 1-3.5 3.5h-9A3.5 3.5 0 0 1 4 18V6a3.5 3.5 0 0 1 3.5-3.5m9 7.5v4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wwf8subge {
  d: path("M10.5 11S7 9 7 6.75c0-1.15.85-2 2-2c.6 0 1.15.25 1.5.75c.35-.5.9-.75 1.5-.75c1.15 0 2 .85 2 2C14 9 10.5 11 10.5 11M7 15.5h6m-6 3h6");
}

</style>
