<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kvc8acc4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:foul" /></template>
<style>
.kvc8acc4f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 8.5h11.5v3.75h-6.25A5.5 5.5 0 1 1 9 8.5ZM9 14h.01M12 2.5v2.75M6.25 3.5L7.5 5.75M17.75 3.5L16.5 5.75");
}

</style>
