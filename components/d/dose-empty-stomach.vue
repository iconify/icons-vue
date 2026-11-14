<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oyonicb2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dose-empty-stomach" /></template>
<style>
.oyonicb2m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 10.5a5 5 0 1 0 10 0a5 5 0 1 0-10 0ZM3.5 8v12M2.25 3.5v3a1.25 1.25 0 0 0 2.5 0v-3m15.75 7.9V3.5c-2 1-2.25 5.5 0 7m-6.212 8.487l4.949-4.949l2.475 2.475l-4.949 4.949Zm2.475-2.474l2.474 2.474");
}

</style>
