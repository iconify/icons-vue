<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="djxqbq8zl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:calm-waves" /></template>
<style>
.djxqbq8zl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 11h18M7.5 11a4.5 4.5 0 0 1 9 0M4 15q3-1.875 6 0t6 0c1.25-.75 2.75-1 4-.5M6 19q3-1.875 6 0t6 0");
}

</style>
