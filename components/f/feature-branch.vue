<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="u0jh89ayv"/><path class="daem5dbgi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:feature-branch" /></template>
<style>
.daem5dbgi {
  d: path("M15 9a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.u0jh89ayv {
  d: path("M7 6.5v11m0-2c0-3 10-1 10-4.5M5 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm0 15a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
