<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u2c_wlqgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:flexible-dates" /></template>
<style>
.u2c_wlqgb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 5h17v15.5h-17ZM8 3v4m8-4v4M3.5 10h17M8 15h8m-8 0l2-2m-2 2l2 2m6-2l-2-2m2 2l-2 2");
}

</style>
