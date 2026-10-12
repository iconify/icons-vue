<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="g66jxprfo"/><rect class="dzcy4xb8q"/><circle class="e4h9difwy"/><circle class="jibjxvl9d"/><path class="tcev49bgw"/><rect class="o6jzkmknc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:column-greek" /></template>
<style>
.dzcy4xb8q {
  width: 6px;
  height: 12.5px;
  x: 9px;
  y: 5.75px;
  rx: 0.5px;
}

.e4h9difwy {
  cx: 4.5px;
  cy: 7.25px;
  r: 1.5px;
}

.g66jxprfo {
  width: 18.5px;
  height: 3px;
  x: 2.75px;
  y: 2.75px;
  rx: 0.75px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jibjxvl9d {
  cx: 19.5px;
  cy: 7.25px;
  r: 1.5px;
}

.o6jzkmknc {
  width: 13px;
  height: 3px;
  x: 5.5px;
  y: 18.25px;
  rx: 0.75px;
}

.tcev49bgw {
  d: path("M12 8.75v6.5");
}

</style>
