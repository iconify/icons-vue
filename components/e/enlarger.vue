<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="r1nabiwky"/><path class="rjo4f0vge"/><rect class="fx56s4bwi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:enlarger" /></template>
<style>
.fx56s4bwi {
  width: 18.5px;
  height: 3px;
  x: 2.75px;
  y: 18.25px;
  rx: 1.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r1nabiwky {
  width: 11px;
  height: 6px;
  x: 3.75px;
  y: 3.25px;
  rx: 1.75px;
}

.rjo4f0vge {
  d: path("M14.75 6.25h3.5m0-3.5v15.5M7 11.75L5.5 15.5m3.75-3.75v3.75m2.25-3.75L13 15.5");
}

</style>
