<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j-zuo3b7q"/><path class="sa9nob41v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:loan-emi-bounce" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j-zuo3b7q {
  d: path("M2.5 7.25a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0m11.5 0h1.5a4.75 4.75 0 0 1 0 9.5h-10");
}

.sa9nob41v {
  d: path("m8 14.25l-2.5 2.5l2.5 2.5m0-13.5C8 5.25 7.5 5 6.75 5S5.5 5.5 5.5 6c0 1.25 2.5.75 2.5 2.5c0 .5-.5 1-1.25 1S5.5 9 5.5 8.75m1.25-4.5V5m0 4.5v.75");
}

</style>
