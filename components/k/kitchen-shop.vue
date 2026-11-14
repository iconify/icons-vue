<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lccy-o2lu"/><path class="v0lzqztqu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:kitchen-shop" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lccy-o2lu {
  d: path("m3.725 8.476l7.25-5.236a1.75 1.75 0 0 1 2.05 0l7.25 5.236A1.75 1.75 0 0 1 21 9.895v9.855a1.75 1.75 0 0 1-1.75 1.75H4.75A1.75 1.75 0 0 1 3 19.75V9.895a1.75 1.75 0 0 1 .725-1.419");
}

.v0lzqztqu {
  d: path("M6 14.75a4 4 0 1 0 8 0a4 4 0 1 0-8 0m8 0h4.25");
}

</style>
