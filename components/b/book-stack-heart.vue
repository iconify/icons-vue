<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y4dfvvbeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:book-stack-heart" /></template>
<style>
.y4dfvvbeq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 2.75h11.5v5H4Zm-1 5h13.75v5H3Zm9.85 10.75H2.5v-5.75h17v.7m-1 8.05l-2.75-2.75a2 2 0 0 1 2.75-2.25a2 2 0 0 1 2.75 2.25Z");
}

</style>
