<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="diyxeuyjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chess-move" /></template>
<style>
.diyxeuyjb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.978 20.101L13.75 16C15.5 11 14 5 9.5 3l-1 1.5C6 5.5 4 8 3 10.5l1.5 2l4-1.5c-.5 2.5-2.5 4-3 5l-1 4.5h9.1m2.9 1l5-5m-4 0h4v4");
}

</style>
