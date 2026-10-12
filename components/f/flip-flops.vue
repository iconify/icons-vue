<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uewkc4bmt"/><path class="kcdnksbih"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:flip-flops" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kcdnksbih {
  d: path("M6.75 5.5v2l-2.5 3.25m2.5-3.25l2.5 3.25m8-5.25v2l-2.5 3.25m2.5-3.25l2.5 3.25");
}

.uewkc4bmt {
  d: path("M6.75 2.75c2.5 0 3.75 2 3.75 4.75c0 2.5-1 3.75-1 6.25c0 3.25.5 7.5-2.75 7.5S4 17 4 13.75C4 11.25 3 10 3 7.5c0-2.75 1.25-4.75 3.75-4.75m10.5 0c2.5 0 3.75 2 3.75 4.75c0 2.5-1 3.75-1 6.25c0 3.25.5 7.5-2.75 7.5S14.5 17 14.5 13.75c0-2.5-1-3.75-1-6.25c0-2.75 1.25-4.75 3.75-4.75");
}

</style>
