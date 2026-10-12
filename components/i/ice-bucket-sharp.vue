<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p2uygm86d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ice-bucket-sharp" /></template>
<style>
.p2uygm86d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 6.25h4.5v4.5H6zm7.5 0H18v4.5h-4.5zm-7.75 4.5h14l-.25 1.48l-1.25 7.54l-.25 1.48H6l-.25-1.48l-1.25-7.54l-.25-1.48zm-1 3.25h14.5");
}

</style>
