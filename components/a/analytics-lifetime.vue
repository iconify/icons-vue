<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fmvuqactg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:analytics-lifetime" /></template>
<style>
.fmvuqactg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.5 15l4-5l3 2.5l6-9m1.125 9h2.25a2.625 2.625 0 0 1 2.625 2.625v3.75a2.625 2.625 0 0 1-2.625 2.625h-2.25A2.625 2.625 0 0 1 14 18.875v-3.75a2.625 2.625 0 0 1 2.625-2.625M14 15.5h7.5m-7.5 3h7.5");
}

</style>
