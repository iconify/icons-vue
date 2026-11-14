<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="twz1a5qvw"/><path class="pigujfort"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:line-ending" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pigujfort {
  d: path("M10.5 13.5L7 17l3.5 3.5");
}

.twz1a5qvw {
  d: path("M3 5h18M3 10h11m5-.5V15q0 2-2 2H7");
}

</style>
