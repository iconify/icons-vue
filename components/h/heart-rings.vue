<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n404ygbaj"/><path class="dg1s8ebfk"/><path class="o61kau_gh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:heart-rings" /></template>
<style>
.dg1s8ebfk {
  d: path("M6.25 15.75a5.75 5.75 0 1 0 11.5 0a5.75 5.75 0 1 0-11.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n404ygbaj {
  d: path("M12 10C9 7.5 7.75 6.25 7.75 4.75s1.25-2.5 2.5-2.5c.75 0 1.5.5 1.75 1.25c.25-.75 1-1.25 1.75-1.25c1.25 0 2.5 1 2.5 2.5S15 7.5 12 10");
}

.o61kau_gh {
  d: path("M9 15.75a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

</style>
