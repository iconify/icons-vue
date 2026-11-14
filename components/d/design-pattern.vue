<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sx-i3gqhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:design-pattern" /></template>
<style>
.sx-i3gqhc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 2.5h6v6h-6Zm13 0h6v6h-6Zm-13 13h6v6h-6Zm13 0h6v6h-6Zm-7-10h7m-10 3v7m13-7v7m-10 3h7");
}

</style>
