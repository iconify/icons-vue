<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-jho2thm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hook-knife" /></template>
<style>
.s-jho2thm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M1.8 19.725L9.225 12.3l2.475 2.475L4.275 22.2Zm7.45-7.475C11.5 8.5 14.5 3 18.75 3c2.5 0 3 3 1.25 5.5l-1.25-1c-2 .25-3.75 2.5-7 7.25Z");
}

</style>
