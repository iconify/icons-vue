<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gg6qr1cwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:feels-like" /></template>
<style>
.gg6qr1cwq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 14V5.25a2.75 2.75 0 0 1 5.5 0V14a4.25 4.25 0 1 1-5.5 0ZM8.5 7.5v7m7.75.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm-1.75 6.5c0-1.5 1.5-2 3.5-2s3.5.5 3.5 2");
}

</style>
