<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tko691b5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:highlighter-pen" /></template>
<style>
.tko691b5z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m16.414 3.343l4.243 4.243l-7.071 7.071l-4.243-4.243Zm-6.364 7.778l2.829 2.829l-1.415 1.414l-4.596-1.061ZM3 19.5h11");
}

</style>
