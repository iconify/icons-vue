<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="la5qfrrxr"/><path class="nd7vd2kjb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bento-box" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.la5qfrrxr {
  width: 18.5px;
  height: 13.5px;
  x: 2.75px;
  y: 5.25px;
  rx: 2.5px;
}

.nd7vd2kjb {
  d: path("M11.75 5.25v13.5m0-6.75h9.5m-14-2a2 2 0 1 1 0 4a2 2 0 1 1 0-4");
}

</style>
