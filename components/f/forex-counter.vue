<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s2ah517db"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:forex-counter" /></template>
<style>
.s2ah517db {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.3 12.5H2.5V10h19v2.5h-.3m-9.4 8H3.5v-8h13.8m-5.3 0v6.3m3-2.55h6m-1.75-1.75L21 16.25m0 3.5h-6m1.75 1.75L15 19.75");
}

</style>
