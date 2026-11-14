<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a36quybtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:away-kit" /></template>
<style>
.a36quybtx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 3L3 5.75L4.75 11L7 10.25V21h10V10.25l2.25.75L21 5.75L15.5 3L12 6.5ZM7 13.5h10M7 17.25h10");
}

</style>
