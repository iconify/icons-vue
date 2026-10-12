<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qq2-rnbik"/><rect class="ydnca8bxv"/><rect class="xn_eiwbum"/><rect class="qlgu63v1q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hash-table" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qlgu63v1q {
  width: 7.75px;
  height: 4.75px;
  x: 13.5px;
  y: 16.5px;
  rx: 1.5px;
}

.qq2-rnbik {
  d: path("m6 6.25l-1 11.5m5-11.5l-1 11.5m-5.5-8h7.25m-8 4.5H10");
}

.xn_eiwbum {
  width: 7.75px;
  height: 4.5px;
  x: 13.5px;
  y: 9.75px;
  rx: 1.5px;
}

.ydnca8bxv {
  width: 7.75px;
  height: 4.75px;
  x: 13.5px;
  y: 2.75px;
  rx: 1.5px;
}

</style>
