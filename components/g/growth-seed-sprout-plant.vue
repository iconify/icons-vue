<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7ffhpkoe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:growth-seed-sprout-plant" /></template>
<style>
.s7ffhpkoe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 18.5a4.5 3 0 1 0 9 0a4.5 3 0 1 0-9 0m4.5-3V8m0 2c0-3.5-2.5-5.5-6.5-5.5C5.5 8 8 10 12 10m0-2c0-3.5 2.5-5.5 6.5-5.5C18.5 6 16 8 12 8");
}

</style>
