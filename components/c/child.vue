<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_pl91b8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:child" /></template>
<style>
.n_pl91b8k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 7.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0ZM3 20.5C3 16.75 5.25 14 8 14s5 2.75 5 6.5m3.5-7.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0ZM16 20.5c0-2 1-3 2.75-3s2.75 1 2.75 3");
}

</style>
