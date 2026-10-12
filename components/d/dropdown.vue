<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="dqkn1u6ne"/><path class="l3n7sdc-q"/><rect class="v39_lcc1n"/><path class="tmpe9up1o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dropdown" /></template>
<style>
.dqkn1u6ne {
  width: 18.5px;
  height: 6px;
  x: 2.75px;
  y: 3.25px;
  rx: 2px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l3n7sdc-q {
  d: path("m15.75 5.5l1.5 1.5l1.5-1.5M6 6.25h5.5");
}

.tmpe9up1o {
  d: path("M6 15h9m-9 3h6");
}

.v39_lcc1n {
  width: 18.5px;
  height: 9px;
  x: 2.75px;
  y: 11.75px;
  rx: 2px;
}

</style>
