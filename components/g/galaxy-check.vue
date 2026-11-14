<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bye8libtl"/><path class="t-gm85b-x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:galaxy-check" /></template>
<style>
.bye8libtl {
  d: path("M10.5 10.5h.01m3.49 0c0-4.75-6.5-6-9.5-3c-2.5 2.5-2 6.5.5 9");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t-gm85b-x {
  d: path("M7 10.5c0 4.75 6.5 6 9.5 3c2.5-2.5 2-6.5-.5-9M14.75 18l2 2L21 15.75");
}

</style>
