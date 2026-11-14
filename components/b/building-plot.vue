<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n3j-5jbko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:building-plot" /></template>
<style>
.n3j-5jbko {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 6.5V3h3.5m11 0H21v3.5m0 11V21h-3.5m-11 0H3v-3.5M10 3h4m7 7v4m-7 7h-4m-7-7v-4m3.5 8V5.5m0 0l7.5 2l-7.5 2Z");
}

</style>
