<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uw1od4kve"/><circle class="og3k95x3a"/><circle class="x9u4_etvk"/><path class="zino02bxb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:coupon-cut" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.og3k95x3a {
  cx: 7px;
  cy: 9px;
  r: 2px;
}

.uw1od4kve {
  d: path("M2.75 6.75a2 2 0 0 1 2-2m14.5 0a2 2 0 0 1 2 2m0 10.5a2 2 0 0 1-2 2m-14.5 0a2 2 0 0 1-2-2m5-12.5h1m2.75 0h1m2.75 0h1m-8.5 14.5h1m2.75 0h1m2.75 0h1m-13.5-9.5v1m0 2.5v1m18.5-4.5v1m0 2.5v1");
}

.x9u4_etvk {
  cx: 7px;
  cy: 15px;
  r: 2px;
}

.zino02bxb {
  d: path("M8.75 10L17 15m-8.25-1L17 9");
}

</style>
