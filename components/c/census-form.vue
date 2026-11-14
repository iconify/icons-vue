<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w_a5jubhp"/><path class="zhodd2wlp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:census-form" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w_a5jubhp {
  d: path("M7 2.5h6.5l6 6V19a2.5 2.5 0 0 1-2.5 2.5H7A2.5 2.5 0 0 1 4.5 19V5A2.5 2.5 0 0 1 7 2.5");
}

.zhodd2wlp {
  d: path("M13.5 2.5v4a2 2 0 0 0 2 2h4M7.439 7.811l.75-.75a1.5 1.5 0 0 1 2.122 0l.75.75a1.5 1.5 0 0 1 .439 1.06v.504a1.125 1.125 0 0 1-1.125 1.125h-2.25A1.125 1.125 0 0 1 7 9.375v-.504a1.5 1.5 0 0 1 .439-1.06M8 13.25h8M8 16h8m-8 2.75h5");
}

</style>
