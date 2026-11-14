<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jws-j7wcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:genre-farming" /></template>
<style>
.jws-j7wcx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3v15m0-9.5c-2.5 0-4.5-2-4.5-4.5C10 4 12 6 12 8.5Zm0 5.5c-2.5 0-4.5-2-4.5-4.5c2.5 0 4.5 2 4.5 4.5Zm0-5.5c2.5 0 4.5-2 4.5-4.5C14 4 12 6 12 8.5Zm0 5.5c2.5 0 4.5-2 4.5-4.5c-2.5 0-4.5 2-4.5 4.5Zm-8 7h16");
}

</style>
