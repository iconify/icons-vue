<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lvu2i-brm"/><path class="tu84ak37k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:condiment-sachets" /></template>
<style>
.lvu2i-brm {
  d: path("M9.5 15.5h-7V4L4 2.5L5.5 4L7 2.5L8.5 4L10 2.5L11.5 4L13 2.5L14.5 4v4.5");
}

.tu84ak37k {
  d: path("M9.5 9.5L11 8l1.5 1.5L14 8l1.5 1.5L17 8l1.5 1.5L20 8l1.5 1.5V20L20 21.5L18.5 20L17 21.5L15.5 20L14 21.5L12.5 20L11 21.5L9.5 20Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
