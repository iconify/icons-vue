<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f_eqobc8w"/><path class="lhzf1klnf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cat-stretch" /></template>
<style>
.f_eqobc8w {
  d: path("M8 17c-2 0-4.5-.5-4.5-2.5V13l.5-3l1.75 1.75l1.75-1.5L8 13c3-.5 6-5 9-5c2 0 2.5 2.5 1.5 5C16 14 12 15 8 17");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lhzf1klnf {
  d: path("M9 16.5L5.5 20h-3m15-6.5V20m1.25-11c1.75-1.5 2.75-3.5 1.75-5.5");
}

</style>
