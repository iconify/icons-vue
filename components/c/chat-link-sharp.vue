<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="m72yl7mlv"/><path class="kdw6k7ubk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chat-link-sharp" /></template>
<style>
.kdw6k7ubk {
  d: path("m12.6 12.97l-1.91 1.91l-1.31 1.155l-2.47-2.47l1.31-1.155l1.91-1.91m3.74 1.2l1.91-1.91l1.155-1.31l-2.47-2.47l-1.155 1.31l-1.91 1.91m-.74 3.21l2.68-2.68");
}

.m72yl7mlv {
  d: path("M12 3.25c4.85 0 8.75 3.5 8.75 7.85s-3.9 7.85-8.75 7.85h-1.616l-1.484-.5L4.6 20l-1.57.523l.67-1.473l1.2-2.9c-1-1.4-1.65-3.15-1.65-5.05c0-4.35 3.9-7.85 8.75-7.85Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
