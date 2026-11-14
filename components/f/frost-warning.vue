<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ymt6i8b8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:frost-warning" /></template>
<style>
.ymt6i8b8h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 5v14M7.75 6.25L9.5 8l1.75-1.75m-3.5 11.5L9.5 16l1.75 1.75m4.312-9.25l-12.124 7m10.167-7.891L12.964 10l2.391.641m-11.71 2.718L6.036 14l-.641 2.391m10.167-.891l-12.124-7m11.917 4.859L12.964 14l.641 2.391m-8.21-8.782L6.036 10l-2.391.641M20 4v10m0 4.25h.01");
}

</style>
