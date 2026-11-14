<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c5vaxactr"/><path class="b_ea0sbbq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:golf-simulator" /></template>
<style>
.b_ea0sbbq {
  d: path("m16.565 6.783l.185.092a.978.978 0 0 1 0 1.75l-.185.092A1.082 1.082 0 0 1 15 7.75a1.082 1.082 0 0 1 1.565-.967");
}

.c5vaxactr {
  d: path("M14.5 2.5H18A3.5 3.5 0 0 1 21.5 6v8a3.5 3.5 0 0 1-3.5 3.5h-3.5A3.5 3.5 0 0 1 11 14V6a3.5 3.5 0 0 1 3.5-3.5M3 6.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m2.5 5.25V16M3 21.5L5.5 16L8 21.5M15 6v8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
