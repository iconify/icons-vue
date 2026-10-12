<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y666f7bxs"/><rect class="li6giibqt"/><path class="l-mw_zb4t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:binoculars" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l-mw_zb4t {
  d: path("M2.75 13.5h7.5m3.5 0h7.5");
}

.li6giibqt {
  width: 3.5px;
  height: 3px;
  x: 10.25px;
  y: 9.5px;
  rx: 0.75px;
}

.y666f7bxs {
  d: path("M2.75 16.75v-8.5a2.5 2.5 0 0 1 2.5-2.5h2.5a2.5 2.5 0 0 1 2.5 2.5v8.5a3.75 3.75 0 0 1-7.5 0m11 0v-8.5a2.5 2.5 0 0 1 2.5-2.5h2.5a2.5 2.5 0 0 1 2.5 2.5v8.5a3.75 3.75 0 0 1-7.5 0");
}

</style>
