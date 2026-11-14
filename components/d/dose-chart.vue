<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="syhi5nbbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dose-chart" /></template>
<style>
.syhi5nbbp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 2.5V21h9.2m-5.7-5v-3.5M10 16V9m3.5 7V5.5m7.152 10.348za1.75 1.75 0 0 1 0 2.475l-2.829 2.829a1.75 1.75 0 0 1-2.475 0a1.75 1.75 0 0 1 0-2.475l2.829-2.829a1.75 1.75 0 0 1 2.475 0m-3.889 1.415l2.474 2.474");
}

</style>
