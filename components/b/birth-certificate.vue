<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="x00qgzx7x"/><circle class="zt548wbiy"/><path class="rrzohjbez"/><circle class="bopak3bua"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:birth-certificate" /></template>
<style>
.bopak3bua {
  cx: 12px;
  cy: 16.75px;
  r: 1.75px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rrzohjbez {
  d: path("M12 12v3");
}

.x00qgzx7x {
  width: 14.5px;
  height: 18.5px;
  x: 4.75px;
  y: 2.75px;
  rx: 2px;
}

.zt548wbiy {
  cx: 12px;
  cy: 8.75px;
  r: 3.25px;
}

</style>
