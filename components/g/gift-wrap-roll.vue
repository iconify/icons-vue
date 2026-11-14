<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zmjc42b1y"/><path class="m8w56wnil"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gift-wrap-roll" /></template>
<style>
.m8w56wnil {
  d: path("M4 5a3.25 1.5 0 1 0 6.5 0A3.25 1.5 0 1 0 4 5Zm6.5 14.5Q12 21 14 21h3.75a2.25 2.25 0 0 0 0-4.5H16.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zmjc42b1y {
  d: path("M4 5v14.5a3.25 1.5 0 0 0 6.5 0V5");
}

</style>
