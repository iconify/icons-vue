<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i29ffoa3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:homebrew-kit" /></template>
<style>
.i29ffoa3x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 8h16v2.5h-16Zm10.916 13.5H7.75q-2 0-2.25-2l-2-9h14l-.022.199M10.5 8V5.5M9 2.5h3v3H9Zm9 11h2v1.75q1.75.75 1.75 2.75v3.75h-5.5V18q0-2 1.75-2.75Z");
}

</style>
