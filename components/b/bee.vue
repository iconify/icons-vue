<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="mqungtowe"/><path class="hlcxkdbtc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bee" /></template>
<style>
.hlcxkdbtc {
  d: path("M18.75 15h2.5M9 10.25v9.5m4.5-9.5v9.5m-2.5-9.5C10 9 6.75 8 6.75 6c0-1.25 1-2 2-2C10.25 4 11 6.5 11 10.25m2 0C14 9 17.25 8 17.25 6c0-1.25-1-2-2-2C13.75 4 13 6.5 13 10.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mqungtowe {
  width: 15px;
  height: 9.5px;
  x: 3.75px;
  y: 10.25px;
  rx: 4.75px;
}

</style>
