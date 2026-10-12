<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-4b13b4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bone-sharp" /></template>
<style>
.m-4b13b4j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.72 14.16l6.44-6.44a2.5 2.5 0 1 1 3.85-1.73a2.5 2.5 0 1 1-1.73 3.85l-6.44 6.44a2.5 2.5 0 1 1-3.85 1.73a2.5 2.5 0 1 1 1.73-3.85Z");
}

</style>
