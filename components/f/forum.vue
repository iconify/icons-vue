<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="a0zu5na2t"/><rect class="v5nfr36ef"/><path class="p2nbr3vxg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:forum" /></template>
<style>
.a0zu5na2t {
  width: 18.5px;
  height: 7px;
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

.p2nbr3vxg {
  d: path("M6 6.25h9m-3.5 11.5H18m-12.5-5.5V16c0 .9.6 1.5 1.25 1.75");
}

.v5nfr36ef {
  width: 13px;
  height: 7px;
  x: 8.25px;
  y: 14.25px;
  rx: 2px;
}

</style>
