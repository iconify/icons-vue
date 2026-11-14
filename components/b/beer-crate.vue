<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s47d43buu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:beer-crate" /></template>
<style>
.s47d43buu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 11.5h18v10H3Zm2.5 0v-3l1-2v-3h1v3l1 2v3m2 0v-3l1-2v-3h1v3l1 2v3m2 0v-3l1-2v-3h1v3l1 2v3m-9 5h5");
}

</style>
