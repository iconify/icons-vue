<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o1z2wccdo"/><path class="nx7cwpbds"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:black-widow" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nx7cwpbds {
  d: path("M12 9.5za.677.677 0 0 1 .629.928l-1.258 3.144A.677.677 0 0 0 12 14.5a.677.677 0 0 0 .629-.928l-1.258-3.144A.677.677 0 0 1 12 9.5m-3.5-1L6 4L3.5 5.5m3.75 5L4 8l-1.5 2.5m4.75 3L4 13l-1.5 3m6-.5l-2.5 2l-1.5 3m11-12L18 4l2.5 1.5m-3.75 5L20 8l1.5 2.5m-4.75 3L20 13l1.5 3m-6-.5l2.5 2l1.5 3");
}

.o1z2wccdo {
  d: path("M7 12a5 5 0 1 0 10 0a5 5 0 1 0-10 0");
}

</style>
