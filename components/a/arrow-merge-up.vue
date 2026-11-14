<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q8-7izo7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:arrow-merge-up" /></template>
<style>
.q8-7izo7a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 20.5v-4c0-3.5 5-3.5 5-7m5 11v-4c0-3.5-5-3.5-5-7m0 0v-6M8.5 7L12 3.5L15.5 7");
}

</style>
