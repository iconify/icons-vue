<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vvrxcokma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:apps" /></template>
<style>
.vvrxcokma {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 3.5h7v7h-7Zm10 3.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm-10 6.5h7v7h-7Zm10 0h7v7h-7Z");
}

</style>
