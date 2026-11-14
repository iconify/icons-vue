<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jg51ih_5u"/><path class="j_34204tq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:city-hall-clock" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j_34204tq {
  d: path("M12 5.25V7l1.5 1M10 21v-2.75a2 2 0 0 1 4 0V21");
}

.jg51ih_5u {
  d: path("M7.75 7a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0M3 21v-7h5.5v-3m7 0v3H21v7M2.5 21h19");
}

</style>
