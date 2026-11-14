<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="keqj2qbqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:artist-at-easel" /></template>
<style>
.keqj2qbqn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3.5h9v9h-9Zm2 9l-1.5 9m6.5-9l1.5 9M3.75 6.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm-1.25 15V16a3.5 3.5 0 0 1 7 0v5.5m-.25-6.75L12 10.5");
}

</style>
