<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="la5qfrrxr"/><path class="twxvwlbnw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:aspect-ratio" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.la5qfrrxr {
  width: 18.5px;
  height: 13.5px;
  x: 2.75px;
  y: 5.25px;
  rx: 2.5px;
}

.twxvwlbnw {
  d: path("M6.25 11.25v-2.5h2.5m9 4v2.5h-2.5");
}

</style>
