<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="opb5z7b6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:humidifier" /></template>
<style>
.opb5z7b6z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 9.5h9V18h-9Zm-2 8.5h13v3.5h-13ZM9 6.75C8 5.5 10 4 9 2.5m3 4.25C11 5.5 13 4 12 2.5m3 4.25C14 5.5 16 4 15 2.5");
}

</style>
