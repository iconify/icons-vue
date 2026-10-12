<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="uqhbdhl_s"/><path class="gvg2d-b3v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:audible-signal" /></template>
<style>
.gvg2d-b3v {
  d: path("M9.25 12V6.5m-2 2l2-2l2 2m-2 7.25v5.5M16.5 6.5a4 4 0 0 1 0 5.5M19 4.5a7 7 0 0 1 0 9.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uqhbdhl_s {
  width: 9px;
  height: 13px;
  x: 4.75px;
  y: 2.75px;
  rx: 2.5px;
}

</style>
