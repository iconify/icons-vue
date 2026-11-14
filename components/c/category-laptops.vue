<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="izfquqbwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:category-laptops" /></template>
<style>
.izfquqbwc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.625 3.5h10.75A2.625 2.625 0 0 1 20 6.125v6.75a2.625 2.625 0 0 1-2.625 2.625H6.625A2.625 2.625 0 0 1 4 12.875v-6.75A2.625 2.625 0 0 1 6.625 3.5M4 15.5h16l1.75 3.25q.25 1-.75 1H3q-1 0-.75-1Z");
}

</style>
