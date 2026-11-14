<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ik9xqux_v"/><path class="yil3u-b5j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:arrow-merge" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ik9xqux_v {
  d: path("M12 3v8l-6 6v4m6-10l6 6v4");
}

.yil3u-b5j {
  d: path("M8.5 6.5L12 3l3.5 3.5");
}

</style>
