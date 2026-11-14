<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u7hkfbc8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bookkeeper" /></template>
<style>
.u7hkfbc8x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0ZM3 20.5c0-4 3-6.5 7.25-6.5c.864 0 1.727.186 2.43.398m2.82-.898h6V22h-6Zm2 2.75h2m-2 3h.01m1.99 0h.01");
}

</style>
