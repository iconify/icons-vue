<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h9y5zbb2c"/><path class="d8vgh5s8x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:banner-promo" /></template>
<style>
.d8vgh5s8x {
  d: path("m8.75 8.25l1 2.5h2.5l-2 1.75L11 15l-2.25-1.5L6.5 15l.75-2.5l-2-1.75h2.5Z");
}

.h9y5zbb2c {
  d: path("M2.5 5.5h19v13h-19ZM15 10h3.75M15 14h3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
