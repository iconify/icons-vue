<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="krvacvcvq"/><path class="hi1e38f1g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:departure-board" /></template>
<style>
.hi1e38f1g {
  d: path("M6 7h3m-3 3.25h3M6 13.5h3M11.75 7H18m-6.25 3.25H18m-6.25 3.25h4M7 16.5v4.75m10-4.75v4.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.krvacvcvq {
  width: 18.5px;
  height: 12.75px;
  x: 2.75px;
  y: 3.75px;
  rx: 2px;
}

</style>
