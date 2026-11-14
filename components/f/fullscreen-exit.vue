<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bumcodb-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fullscreen-exit" /></template>
<style>
.bumcodb-m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 3.5V6A2.5 2.5 0 0 1 6 8.5H3.5m12-5V6A2.5 2.5 0 0 0 18 8.5h2.5m0 7H18a2.5 2.5 0 0 0-2.5 2.5v2.5m-12-5H6A2.5 2.5 0 0 1 8.5 18v2.5");
}

</style>
