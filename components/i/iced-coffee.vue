<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wc1yxsb3w"/><path class="g3vb4cckb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:iced-coffee" /></template>
<style>
.g3vb4cckb {
  d: path("M15.25 11H17a2.5 2.5 0 0 1 0 5h-1.9M7.75 2.75c-.6.6-.6 1.6 0 2.25s.6 1.6 0 2.25m3.5-4.5c-.6.6-.6 1.6 0 2.25s.6 1.6 0 2.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wc1yxsb3w {
  d: path("M3.75 9.75h11.5v5.75A5.25 5.25 0 0 1 10 20.75H9a5.25 5.25 0 0 1-5.25-5.25Z");
}

</style>
