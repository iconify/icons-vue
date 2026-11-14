<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="crfzejbau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:air-duct" /></template>
<style>
.crfzejbau {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.5 16V9.5h-11V3H17a3 3 0 0 1 3 3v10m-9 0h11m-8.5 3v2.5m3.25-2.5v2.5M20 19v2.5");
}

</style>
