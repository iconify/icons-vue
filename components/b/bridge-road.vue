<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="xzy2sn-tx"/><path class="p4que1bfc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bridge-road" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p4que1bfc {
  d: path("M5 18a9 9 0 0 1 14 0M5 11.75V18m14-6.25V18M9 11.75v3.4m3-3.4v2.9m3-2.9v3.4M7.5 20.5c.6-.6 1.4-.6 2 0s1.4.6 2 0m1 0c.6-.6 1.4-.6 2 0s1.4.6 2 0");
}

.xzy2sn-tx {
  width: 18.5px;
  height: 2.5px;
  x: 2.75px;
  y: 9.25px;
  rx: 0.75px;
}

</style>
