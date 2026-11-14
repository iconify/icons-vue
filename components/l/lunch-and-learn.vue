<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v95jsrn6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lunch-and-learn" /></template>
<style>
.v95jsrn6v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 10.5c0-2.5 2-3.5 4-3.5s4 1 4 3.5Zm1.25 5h5.5a1.25 1.25 0 0 1 1.25 1.25A1.25 1.25 0 0 1 9.25 18h-5.5a1.25 1.25 0 0 1-1.25-1.25a1.25 1.25 0 0 1 1.25-1.25M2.5 13c1-1 2 1 3 0s2 1 3 0s2 .5 2 0m7.25-4.5c-1-1-2.5-1.25-4.25-1v9c1.75-.25 3.25 0 4.25 1c1-1 2.5-1.25 3.75-1v-9c-1.25-.25-2.75 0-3.75 1m0 0v9");
}

</style>
