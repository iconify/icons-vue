<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cjqfe5bpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:do-not-iron" /></template>
<style>
.cjqfe5bpz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 17.5c.5-4.5 3-7.5 7-7.5H20v7.5ZM11 10V8a2 2 0 0 1 2-2h7v4M4 3.5l16 16m0-16l-16 16");
}

</style>
