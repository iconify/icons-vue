<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pwpi0db1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:magnet-snap" /></template>
<style>
.pwpi0db1z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 3.5h4v7a2.5 2.5 0 0 0 5 0v-7h4v7a6.5 6.5 0 0 1-13 0Zm0 3.5h4m5 0h4M3 20.5h4m3 0h4m3 0h4");
}

</style>
