<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c56tmmbwu"/><path class="atk-bcczd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:currency-exchange-booth" /></template>
<style>
.atk-bcczd {
  d: path("M11.7 14H6.5V9H13v4.2m-7.5 2.55h6.2m2.8.25h7m-1.75-1.75L21.5 16l-1.75 1.75M21.5 20h-7m1.75-1.75L14.5 20l1.75 1.75");
}

.c56tmmbwu {
  d: path("M2.5 2.5h19v4h-19Zm1.5 4v15h7.7M20 10.6V6.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
