<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h8353tdkv"/><path class="j-bp5ef8a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:letter-tiles" /></template>
<style>
.h8353tdkv {
  d: path("M2.5 7h8v10h-8Zm11 0h8v10h-8Z");
}

.j-bp5ef8a {
  d: path("m4.5 14l2-4.5l2 4.5m-3.25-1.5h2.5m9.75-3V14");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
