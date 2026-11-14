<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qyoaohkvq"/><path class="fm1ow8__f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bassist" /></template>
<style>
.fm1ow8__f {
  d: path("m11.964 10.268l5.304-5.304a1.25 1.25 0 0 1 1.768 0a1.25 1.25 0 0 1 0 1.768l-5.304 5.304a1.25 1.25 0 0 1-1.768 0a1.25 1.25 0 0 1 0-1.768M17.5 3.5l3 3M6.25 14.25l3.5 3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qyoaohkvq {
  d: path("M2.5 16a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0");
}

</style>
