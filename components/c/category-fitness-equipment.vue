<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-wocab0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:category-fitness-equipment" /></template>
<style>
.f-wocab0r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 12h10M5.25 8.5zA1.75 1.75 0 0 1 7 10.25v3.5a1.75 1.75 0 0 1-1.75 1.75a1.75 1.75 0 0 1-1.75-1.75v-3.5A1.75 1.75 0 0 1 5.25 8.5m13.5 0za1.75 1.75 0 0 1 1.75 1.75v3.5a1.75 1.75 0 0 1-1.75 1.75A1.75 1.75 0 0 1 17 13.75v-3.5a1.75 1.75 0 0 1 1.75-1.75M2.5 10v4m19-4v4");
}

</style>
