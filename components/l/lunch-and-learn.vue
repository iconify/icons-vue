<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="myj27yb5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lunch-and-learn" /></template>
<style>
.myj27yb5x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 10.5c0-2.5 2-3.5 4-3.5s4 1 4 3.5Zm0 5h8V18h-8Zm0-2.5c1-1 2 1 3 0s2 1 3 0s2 .5 2 0m7.25-4.5c-1-1-2.5-1.25-4.25-1v9c1.75-.25 3.25 0 4.25 1c1-1 2.5-1.25 3.75-1v-9c-1.25-.25-2.75 0-3.75 1Zm0 0v9");
}

</style>
