<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b8_qqnb0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:half-bath" /></template>
<style>
.b8_qqnb0k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 3h5v9h-5Zm0 9h16c0 3.5-2 5.5-5 6v3.5h-6v-3.75c-3-.75-5-2.75-5-5.75Zm5-2.5h11M5 6h2");
}

</style>
