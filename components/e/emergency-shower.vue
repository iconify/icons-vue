<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="a_-q_pb0z"/><path class="a0ccnsbdj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:emergency-shower" /></template>
<style>
.a_-q_pb0z {
  width: 18.5px;
  height: 18.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 3px;
}

.a0ccnsbdj {
  d: path("M7 18.25v-12h5.5v1.5m-2.5 1h5M11 11v1.5m1.5-1.5v3m1.5-3v1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
