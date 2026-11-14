<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mmnruhbzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:emergency-gas-valve" /></template>
<style>
.mmnruhbzq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18.2 11.5H2.5V7h6V4.5h7V7h6v4.5h-1.7m-7.8-7v-2m-3.5 0h7m6.25 14a2.75 2.75 0 1 1-2.25-2.25M17 19l-2.5 2.5");
}

</style>
