<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wkcdjqbmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:donate-in-memory" /></template>
<style>
.wkcdjqbmz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 10h6v11H9ZM5.5 21h13M12 8.25c-1.25 0-2-.75-2-2s1-2.25 2-3.5C13 4 14 5 14 6.25s-.75 2-2 2Zm0 0V10");
}

</style>
