<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v-e9mrnkf"/><rect class="fe4xh4bkm"/><rect class="ttazsxb5o"/><path class="do_z1zwrk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cooler-box" /></template>
<style>
.do_z1zwrk {
  d: path("M9.25 14.25h5.5");
}

.fe4xh4bkm {
  width: 18.5px;
  height: 4px;
  x: 2.75px;
  y: 6.75px;
  rx: 1.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ttazsxb5o {
  width: 15.5px;
  height: 10.5px;
  x: 4.25px;
  y: 10.75px;
  rx: 2px;
}

.v-e9mrnkf {
  d: path("M5.25 6.75v-1.5a2.5 2.5 0 0 1 2.5-2.5h8.5a2.5 2.5 0 0 1 2.5 2.5v1.5");
}

</style>
