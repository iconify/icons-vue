<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b20sm0b7w"/><circle class="soixedczn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:goal-check" /></template>
<style>
.b20sm0b7w {
  d: path("M2.75 20.25V5.75a1 1 0 0 1 1-1h16.5a1 1 0 0 1 1 1v14.5M7.5 4.75v7.5m4.5-7.5v7.5m4.5-7.5v7.5M2.75 8.5h18.5m-18.5 3.75h18.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.soixedczn {
  cx: 12px;
  cy: 17.5px;
  r: 2.75px;
}

</style>
