<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n__b4fbza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:check-in-qr" /></template>
<style>
.n__b4fbza {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 3h7v7H3Zm11 0h7v7h-7ZM3 14h7v7H3Zm3.5-7.5h.01m10.99 0h.01M6.5 17.5h.01m8.24.5l2 2L21 15.75");
}

</style>
