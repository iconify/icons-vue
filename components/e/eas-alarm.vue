<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j8hfkph-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:eas-alarm" /></template>
<style>
.j8hfkph-z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 6h7v14h-7Zm-2 15.5h11M10 6V5a2 2 0 0 1 4 0v1M7.237 9.25a5.5 5.5 0 0 1 0-5.5m9.526 0a5.5 5.5 0 0 1 0 5.5m-12.467.842a8.5 8.5 0 0 1 0-7.184m15.408 0a8.5 8.5 0 0 1 0 7.184");
}

</style>
