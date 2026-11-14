<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qontlkb7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hippo-face" /></template>
<style>
.qontlkb7r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 11V7a2 2 0 0 1 2-2a1.5 1.5 0 0 1 3 0h3a1.5 1.5 0 0 1 3 0a2 2 0 0 1 2 2v4c2.5.5 3 2.5 3 5c0 3.5-3.5 5-9.5 5s-9.5-1.5-9.5-5c0-2.5.5-4.5 3-5Zm3-2.5h.01m6.99 0h.01M9 16h.01M15 16h.01");
}

</style>
