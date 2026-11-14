<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m1n28fouj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:diaper-change" /></template>
<style>
.m1n28fouj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 4.75h13.5V8c-2.75.5-4.5 2.75-5 6.5H7.75C7.5 10.75 5.5 8.5 3 8Zm0 2h13.5m-2 9.25H21m-1.75-1.75L21 16l-1.75 1.75M21.5 20H15m1.75-1.75L15 20l1.75 1.75");
}

</style>
