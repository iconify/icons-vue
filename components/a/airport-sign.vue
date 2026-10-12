<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="a_-q_pb0z"/><path class="symk1vbtw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:airport-sign" /></template>
<style>
.a_-q_pb0z {
  width: 18.5px;
  height: 18.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 3px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.symk1vbtw {
  d: path("M12 5c.75 0 1.25.75 1.25 1.75v3l5 3v2.5l-5-1.25v2l1.5 1.25v1.25L12 17.75l-2.75.75v-1.25l1.5-1.25v-2l-5 1.25v-2.5l5-3v-3c0-1 .5-1.75 1.25-1.75");
}

</style>
