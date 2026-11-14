<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j3ks0cc4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chemistry" /></template>
<style>
.j3ks0cc4q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 2.5H10v6l-5.5 10Q3.5 21 6 21h12q2.5 0 1.5-2.5L14 8.5v-6h1.5m-8.75 12h10.5");
}

</style>
