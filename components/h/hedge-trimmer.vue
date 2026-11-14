<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="irm52fbrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hedge-trimmer" /></template>
<style>
.irm52fbrm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 10.75h7v5H3Zm1.5 0v-2.5a1.5 1.5 0 0 1 3 0v2.5m2.5 1.5l1.5-1.5l1.5 1.5l1.5-1.5l1.5 1.5l1.5-1.5l1.5 1.5h1.5a1 1 0 0 1 0 2H19l-1.5 1.5l-1.5-1.5l-1.5 1.5l-1.5-1.5l-1.5 1.5l-1.5-1.5");
}

</style>
