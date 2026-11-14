<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jxez7vbyj"/><path class="xkuuyv67s"/><path class="t1jzpjbyn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hospital-clown" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jxez7vbyj {
  d: path("M4.5 12.5a7.5 7.5 0 1 0 15 0a7.5 7.5 0 1 0-15 0");
}

.t1jzpjbyn {
  d: path("M9.25 9.75h.01m5.49 0h.01m-7.01 5.5c1.75 3 6.75 3 8.5 0M4 8.75l-1.5 1.5l1.5 1.5l-1.5 1.5l1.5 1.5m16-6l1.5 1.5l-1.5 1.5l1.5 1.5l-1.5 1.5");
}

.xkuuyv67s {
  fill: currentColor;
  d: path("M10.25 12.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

</style>
