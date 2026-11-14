<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fg1crp_rh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:git-diff" /></template>
<style>
.fg1crp_rh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 2.5h3l3 3v8a2 2 0 0 1-2 2h-4a2 2 0 0 1-2-2v-9a2 2 0 0 1 2-2Zm11 0h3l3 3v8a2 2 0 0 1-2 2h-4a2 2 0 0 1-2-2v-9a2 2 0 0 1 2-2ZM5 10h3m8 0h3m-1.5-1.5v3M6.75 18.25L5 20l1.75 1.75M5 20h14m-1.75-1.75L19 20l-1.75 1.75");
}

</style>
