<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i7u9zxbqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:category-sustainable" /></template>
<style>
.i7u9zxbqu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 14c-5.5 0-8.5-2.5-8.5-7.5C9 6.5 12 9 12 14Zm0-3c0-5 3-8 8.5-8c0 5.5-3 8-8.5 8Zm0 3v3m-8 4c1.5-3.25 4.5-4 8-4s6.5.75 8 4Z");
}

</style>
