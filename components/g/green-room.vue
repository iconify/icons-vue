<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uy8q9_o0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:green-room" /></template>
<style>
.uy8q9_o0z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 3h12v14H6Zm6 14v3.5m-3.5 0h7M2.5 7A1.75 1.75 0 0 1 6 7a1.75 1.75 0 0 1-3.5 0Zm0 6A1.75 1.75 0 0 1 6 13a1.75 1.75 0 0 1-3.5 0ZM18 7a1.75 1.75 0 0 1 3.5 0A1.75 1.75 0 0 1 18 7Zm0 6a1.75 1.75 0 0 1 3.5 0a1.75 1.75 0 0 1-3.5 0Z");
}

</style>
