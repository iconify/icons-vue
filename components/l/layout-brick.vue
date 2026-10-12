<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="bvp3hnb7f"/><rect class="p268vfc6t"/><rect class="l9yczbbvh"/><rect class="ayo9k_bwn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:layout-brick" /></template>
<style>
.ayo9k_bwn {
  width: 7.75px;
  height: 10.5px;
  x: 13.5px;
  y: 10.75px;
  rx: 2px;
}

.bvp3hnb7f {
  width: 7.75px;
  height: 10.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 2px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l9yczbbvh {
  width: 7.75px;
  height: 5px;
  x: 13.5px;
  y: 2.75px;
  rx: 2px;
}

.p268vfc6t {
  width: 7.75px;
  height: 5px;
  x: 2.75px;
  y: 16.25px;
  rx: 2px;
}

</style>
