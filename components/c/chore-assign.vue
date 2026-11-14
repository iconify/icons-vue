<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eof1n64px"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chore-assign" /></template>
<style>
.eof1n64px {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0ZM3 21c0-4.5 3.5-7 7.5-7c1.863 0 3.51.521 4.737 1.32M14.5 18.5h7m-2.75-2.75l2.75 2.75l-2.75 2.75");
}

</style>
