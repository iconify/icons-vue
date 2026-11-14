<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lhi8l_31r"/><path class="t6h1r3bno"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:capuchin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lhi8l_31r {
  d: path("M4.75 14a7.5 7.5 0 0 0 14.5 0c2.75.25 2.75-4.25 0-4a7.5 7.5 0 0 0-14.5 0C2 9.75 2 14.25 4.75 14");
}

.t6h1r3bno {
  d: path("M4.75 10C7.5 8.5 10 8.5 12 10.5c2-2 4.5-2 7.25-.5m-10 3.5h.01m5.49 0h.01");
}

</style>
