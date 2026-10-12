<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="re9og6ryj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:catheter-sharp" /></template>
<style>
.re9og6ryj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 7.75V9.5C5.25 13 7.5 15 11 15h3c1.5 0 2-2.75 3.75-2.75M14 15c1.5 0 2 2.75 3.75 2.75m0-6.75h3.5v2.5h-3.5zm0 5.5h3.5V19h-3.5zM5.25 2.75a2 2.5 0 1 1 0 5a2 2.5 0 1 1 0-5Z");
}

</style>
