<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uodah_b1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:house-number" /></template>
<style>
.uodah_b1z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.944 20.5H3.5v-10L12 3.25l8.5 7.25v1.756M17 15l-.75 6.5M20 15l-.75 6.5M15 17h6.25m-6.5 2.75H21");
}

</style>
