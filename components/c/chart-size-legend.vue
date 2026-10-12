<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="sn04cubqj"/><path class="x78nu8bzo"/><rect class="atr8gwj0w"/><rect class="v8sy-w-8a"/><path class="bu5z8dh8n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chart-size-legend" /></template>
<style>
.atr8gwj0w {
  width: 3px;
  height: 3px;
  x: 2.75px;
  y: 12.75px;
  rx: 1px;
}

.bu5z8dh8n {
  d: path("M9 14.25h8m-8 5.5h5.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sn04cubqj {
  width: 18.5px;
  height: 7px;
  x: 2.75px;
  y: 2.75px;
  rx: 1.5px;
}

.v8sy-w-8a {
  width: 3px;
  height: 3px;
  x: 2.75px;
  y: 18.25px;
  rx: 1px;
}

.x78nu8bzo {
  d: path("M7 7.25V6m7 1.25V5.5m-3.5 1.75v-2.5");
}

</style>
