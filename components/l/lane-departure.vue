<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lb1xdjb4z"/><path class="n64r3nqcd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lane-departure" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lb1xdjb4z {
  d: path("M3.5 20.5L8 3.5m12.5 17L16 3.5M10 20c0-4.5 3-8.25 9.5-11");
}

.n64r3nqcd {
  d: path("M16.25 7.5L19.5 9l-1.75 3");
}

</style>
