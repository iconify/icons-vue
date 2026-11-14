<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pfq8yoh9v"/><path class="zpsn0dnxv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:drinks-aisle" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pfq8yoh9v {
  d: path("M2.5 2.5h19M7 2.5V6m10-3.5V6M6 6h12a3.5 3.5 0 0 1 3.5 3.5v8A3.5 3.5 0 0 1 18 21H6a3.5 3.5 0 0 1-3.5-3.5v-8A3.5 3.5 0 0 1 6 6");
}

.zpsn0dnxv {
  d: path("M10.938 9h2.125a2.19 2.19 0 0 1 2.187 2.188v4.875a2.19 2.19 0 0 1-2.187 2.187h-2.125a2.19 2.19 0 0 1-2.188-2.187v-4.875A2.19 2.19 0 0 1 10.938 9M8.75 11.5h6.5m-6.5 4.25h6.5");
}

</style>
