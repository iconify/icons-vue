<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="udk4qshgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:garden-kneeler-stool" /></template>
<style>
.udk4qshgk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 13h19v4h-19Zm2 0V6.5a2 2 0 0 1 4 0V13m7 0V6.5a2 2 0 0 1 4 0V13M5 17l-1.5 4.5M19 17l1.5 4.5");
}

</style>
