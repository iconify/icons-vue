<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t8kss_bzq"/><path class="nv7g9ccxh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:grocery-cart-full" /></template>
<style>
.nv7g9ccxh {
  d: path("M2.5 3.5h2L7 15m0 4a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm8 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM8 2.5h4V7H8ZM14 7q0-3.75 4.5-4.5C18.5 5 17 6.75 14 7");
}

.t8kss_bzq {
  d: path("M5.25 7H20.5l-1.75 8H7Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
