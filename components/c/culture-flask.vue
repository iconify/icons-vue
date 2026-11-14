<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="emoilrbka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:culture-flask" /></template>
<style>
.emoilrbka {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 3H10v5.75L4.25 19a1.75 1.75 0 0 0 1.5 2.5h12.5a1.75 1.75 0 0 0 1.5-2.5L14 8.75V3h1.25M7 14h10");
}

</style>
