<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fsurxm6vb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:adopt-a-whale" /></template>
<style>
.fsurxm6vb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 11c0-3 3-4.5 6.5-4.5s5.5 2 7.5 4L20 7l1.5 5l-4.5.25c-2.5 2.25-6 3.25-9.5 3.25c-3 0-5-1.5-5-4.5ZM7 4c0-1.25-1.25-1.75-2.25-1.75M7 4c0-1.25 1.25-1.75 2.25-1.75M6 10.5h.01M18 21.75l-2.5-2.5a1.75 1.75 0 1 1 2.5-2.5a1.75 1.75 0 1 1 2.5 2.5Z");
}

</style>
