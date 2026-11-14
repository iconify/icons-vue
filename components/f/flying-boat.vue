<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rzj6j7zxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:flying-boat" /></template>
<style>
.rzj6j7zxw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 4l3.5 4H18c2 0 3 1 3 2s-1 1.5-2.5 1.5H7Zm7 1h7m-3.5 0v3M3 15q1.5-1.5 3 0t3 0t3 0t3 0t3 0t3 0M3 19.25q1.5-1.5 3 0t3 0t3 0t3 0t3 0t3 0");
}

</style>
