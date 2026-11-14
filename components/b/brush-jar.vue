<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dnzfmabjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:brush-jar" /></template>
<style>
.dnzfmabjt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 11h9l1 2v6a2.5 2.5 0 0 1-2.5 2.5H9A2.5 2.5 0 0 1 6.5 19v-6Zm4.5 0V6c-1.5-1-1.5-2.5 0-3.5c1.5 1 1.5 2.5 0 3.5m-3 5L6.5 4.5M15 11l2.5-6.5");
}

</style>
