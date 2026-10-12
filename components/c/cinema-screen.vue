<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bkw0vcbrm"/><rect class="rfbj_-bad"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cinema-screen" /></template>
<style>
.bkw0vcbrm {
  d: path("M2.75 3.75h2.5c0 5.5.5 11 1.75 16.5H2.75Zm18.5 0h-2.5c0 5.5-.5 11-1.75 16.5h4.25Zm-16 0h13.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rfbj_-bad {
  width: 6.5px;
  height: 4.5px;
  x: 8.75px;
  y: 7.75px;
  rx: 1.25px;
}

</style>
