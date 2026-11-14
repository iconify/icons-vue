<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="axgjabb6n"/><path class="gz8vocb7r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:amethyst-cluster" /></template>
<style>
.axgjabb6n {
  d: path("M8.75 20.5V8L12 3l3.25 5v12.5M8.75 15L4.5 9.5l-1.75 3.75L5.5 20.5m9.75-5.5l4.25-5.5l1.75 3.75l-2.75 7.25m-15 0h17");
}

.gz8vocb7r {
  d: path("M8.75 8L12 10l3.25-2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
