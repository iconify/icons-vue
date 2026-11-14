<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ti61cnbyn"/><path class="nvy0qd86y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hockey-puck" /></template>
<style>
.nvy0qd86y {
  d: path("M3.5 10v4c0 2.5 3.75 4.5 8.5 4.5s8.5-2 8.5-4.5v-4");
}

.ti61cnbyn {
  d: path("M3.5 10a8.5 3.5 0 1 0 17 0a8.5 3.5 0 1 0-17 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
