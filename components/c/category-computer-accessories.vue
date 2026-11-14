<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hq6vs_piu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:category-computer-accessories" /></template>
<style>
.hq6vs_piu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3.5za5 5 0 0 1 5 5v5a5 5 0 0 1-5 5a5 5 0 0 1-5-5v-5a5 5 0 0 1 5-5m0 0V10m-5 0h10");
}

</style>
