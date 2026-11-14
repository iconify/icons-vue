<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kkb3b2-9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bathroom" /></template>
<style>
.kkb3b2-9k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 2.5h10v7H7ZM3.5 15h17v1c0 3.5-4 5.5-8.5 5.5s-8.5-2-8.5-5.5Zm12 0v-2.25c0-1.25-2.5-1.25-3 0");
}

</style>
