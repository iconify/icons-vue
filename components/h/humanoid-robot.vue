<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_m6g7xwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:humanoid-robot" /></template>
<style>
.h_m6g7xwb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 2.5h8v6H8Zm-1 8.75h10v6.5H7ZM7 13l-2.5 2.5V18M17 13l2.5 2.5V18m-9.5-.25v3.75m4-3.75v3.75m-3.25-16h2.5");
}

</style>
