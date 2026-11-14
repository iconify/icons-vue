<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xie48obnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:category-storage" /></template>
<style>
.xie48obnq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 4h13A2.5 2.5 0 0 1 21 6.5A2.5 2.5 0 0 1 18.5 9h-13A2.5 2.5 0 0 1 3 6.5A2.5 2.5 0 0 1 5.5 4m1.625 5h9.75a2.625 2.625 0 0 1 2.625 2.625v6.25a2.625 2.625 0 0 1-2.625 2.625h-9.75A2.625 2.625 0 0 1 4.5 17.875v-6.25A2.625 2.625 0 0 1 7.125 9M9.5 13.5h5");
}

</style>
