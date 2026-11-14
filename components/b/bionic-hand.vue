<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zmq3jcxbg"/><path class="e6c5db_ak"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bionic-hand" /></template>
<style>
.e6c5db_ak {
  d: path("M11.25 16.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m2.5 0H15");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zmq3jcxbg {
  d: path("M17 12v3.5c0 3.25-2.25 6-5.25 6c-2.75 0-4.25-1.25-5.5-3.25l-2.5-3.75c-.5-1 0-2 1-2.25c.75-.25 1.5.25 2 1l2 2.25v-4m0-1.25V9m0-1.5V6m3 3.5v-2m0-1.5V4m3 5.5V8m0-1.5V4.75M17 10.5V9.25m0-1.5V7");
}

</style>
