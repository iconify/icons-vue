<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="zmkaagbvv"/><rect class="sriu-7b3c"/><rect class="hu_ntz_gp"/><rect class="my527lywx"/><rect class="ttugeiezt"/><path class="v7fe81b1x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:container" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hu_ntz_gp {
  width: 4px;
  height: 4px;
  x: 17px;
  y: 12px;
  rx: 1px;
}

.my527lywx {
  width: 4px;
  height: 4px;
  x: 6.5px;
  y: 5px;
  rx: 1px;
}

.sriu-7b3c {
  width: 4px;
  height: 4px;
  x: 10px;
  y: 12px;
  rx: 1px;
}

.ttugeiezt {
  width: 4px;
  height: 4px;
  x: 13.5px;
  y: 5px;
  rx: 1px;
}

.v7fe81b1x {
  d: path("M2.75 19.25h18.5");
}

.zmkaagbvv {
  width: 4px;
  height: 4px;
  x: 3px;
  y: 12px;
  rx: 1px;
}

</style>
