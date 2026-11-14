<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lrpnsrb3k"/><path class="amv2qob3y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hand-wrapped" /></template>
<style>
.amv2qob3y {
  d: path("M4.5 11.5H13a1.75 1.75 0 0 1 0 3.5h-3M4.5 8.5h15m-12 10h9");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lrpnsrb3k {
  d: path("M7.5 21.5V16c-2-1-3-3-3-5V7A3.75 3.75 0 0 1 12 7a3.75 3.75 0 0 1 7.5 0v5c0 2-1.5 3.5-3 4v5.5");
}

</style>
