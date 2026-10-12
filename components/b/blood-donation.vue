<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h160igils"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:blood-donation" /></template>
<style>
.h160igils {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 13.75v7.5m3-6.5h2.5l2.1-1.1a2 2 0 0 1 .95-.25h2.45a1.5 1.5 0 0 1 0 3H11.5m-5.75 4.35h6.6a3 3 0 0 0 1.85-.65l5.6-4.4a1.5 1.5 0 0 0-1.85-2.35l-3.2 2.5M13.5 2.75c1.1 1.6 3 3.4 3 5.25a3 3 0 0 1-6 0c0-1.85 1.9-3.65 3-5.25");
}

</style>
