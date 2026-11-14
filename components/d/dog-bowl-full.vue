<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-j6mtbgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dog-bowl-full" /></template>
<style>
.v-j6mtbgj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 11.5h18.5l-2.25 7H5Zm2.25 0A3 3 0 0 1 9.5 8a2.5 2.5 0 0 1 5 0a3 3 0 0 1 4.5 3.5");
}

</style>
