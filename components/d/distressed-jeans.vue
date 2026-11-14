<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cwtxecb9j"/><path class="arbtnbcve"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:distressed-jeans" /></template>
<style>
.arbtnbcve {
  d: path("M4.25 14L6 15.25l1.75-1.5l1.75 1.5L11.25 14");
}

.cwtxecb9j {
  d: path("M5 2.5h14l1.5 19h-6.75L12 9.5l-1.75 12H3.5ZM5 6h14");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
