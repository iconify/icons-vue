<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gzgfxrblh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lettuce-sharp" /></template>
<style>
.gzgfxrblh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 18.8a2.48 2.48 0 0 1-2.85-2.99a2.65 2.65 0 0 1-.89-4.32A2.62 2.62 0 0 1 6.9 7.35a2.43 2.43 0 0 1 3.18-2.51a2.31 2.31 0 0 1 3.84 0a2.43 2.43 0 0 1 3.18 2.51a2.62 2.62 0 0 1 1.39 4.14a2.65 2.65 0 0 1-.89 4.32a2.48 2.48 0 0 1-2.85 2.99L12 21ZM12 21V8.5");
}

</style>
