<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oatbfvp5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ice-hockey-stick" /></template>
<style>
.oatbfvp5a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m18.5 2.5l-8.25 13m0 0l-1.5 3H3.5q-1 0-1-1q0-2 2.5-2ZM3 21.5h18");
}

</style>
