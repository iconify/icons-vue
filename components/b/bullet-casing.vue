<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nabearn8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bullet-casing" /></template>
<style>
.nabearn8w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m10 9l-2 2.5V19h8v-7.5L14 9Zm0 0V6.5c0-2.25 1-4 2-4s2 1.75 2 4V9M7 19h10v2.5H7Z");
}

</style>
