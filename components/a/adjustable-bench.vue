<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hh75lbc7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:adjustable-bench" /></template>
<style>
.hh75lbc7h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 11h9a1.5 1.5 0 0 1 1.5 1.5A1.5 1.5 0 0 1 13 14H4a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 4 11m11.116-1.088l2.915-5.144A1.42 1.42 0 0 1 20 4.25a1.423 1.423 0 0 1 .47 1.982l-3.301 5.212a1.155 1.155 0 0 1-1.669.306a1.42 1.42 0 0 1-.384-1.838M4.5 14v6.5m8-6.5v6.5");
}

</style>
