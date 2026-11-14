<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lwdyqlgjv"/><path class="fun2n4bvk"/><path class="zln3d7vmq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hospital-security" /></template>
<style>
.fun2n4bvk {
  fill: currentColor;
  d: path("M8 6.75c0-2.5 1.75-4.25 4-4.25s4 1.75 4 4.25Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lwdyqlgjv {
  d: path("M4 20c0-3.25 3.5-5.5 8-5.5s8 2.25 8 5.5c0 .6-.4 1-1 1H5c-.6 0-1-.4-1-1M8 7.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0");
}

.zln3d7vmq {
  d: path("M6.75 7.25h10.5m-4.927 9.18za1.38 1.38 0 0 0 1.07.777a.358.358 0 0 1 .2.615a1.38 1.38 0 0 0-.409 1.258a.358.358 0 0 1-.523.38a1.38 1.38 0 0 0-1.322 0a.358.358 0 0 1-.523-.38a1.38 1.38 0 0 0-.409-1.258a.358.358 0 0 1 .2-.615a1.38 1.38 0 0 0 1.07-.777a.358.358 0 0 1 .646 0");
}

</style>
