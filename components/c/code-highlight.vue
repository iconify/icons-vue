<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w_a5jubhp"/><path class="ubr3mw63z"/><path class="klug8zbmm"/><path class="nh1i2bbzg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:code-highlight" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.klug8zbmm {
  fill: currentColor;
  d: path("M9 11h4a1.5 1.5 0 0 1 1.5 1.5A1.5 1.5 0 0 1 13 14H9a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 9 11m6.5.75za.937.937 0 0 1 0 1.5a.625.625 0 0 1-1-.5v-.5a.625.625 0 0 1 1-.5");
}

.nh1i2bbzg {
  d: path("M8 18h6");
}

.ubr3mw63z {
  d: path("M13.5 2.5v4a2 2 0 0 0 2 2h4M8 6.5h3.5");
}

.w_a5jubhp {
  d: path("M7 2.5h6.5l6 6V19a2.5 2.5 0 0 1-2.5 2.5H7A2.5 2.5 0 0 1 4.5 19V5A2.5 2.5 0 0 1 7 2.5");
}

</style>
