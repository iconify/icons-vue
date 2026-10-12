<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="g6ctus9qt"/><rect class="cwglfxbbx"/><circle class="a24yqwbfv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:magazine" /></template>
<style>
.a24yqwbfv {
  cx: 12px;
  cy: 14.75px;
  r: 3.25px;
}

.cwglfxbbx {
  width: 10.5px;
  height: 3px;
  x: 6.75px;
  y: 5.75px;
  rx: 1px;
}

.g6ctus9qt {
  width: 16.5px;
  height: 18.5px;
  x: 3.75px;
  y: 2.75px;
  rx: 2.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
