<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jzvu6abpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:garden-statue" /></template>
<style>
.jzvu6abpn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 6a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0ZM6 16.5c0-3 2.5-4.5 6-4.5s6 1.5 6 4.5Zm2 0v3H6.5v2h11v-2H16v-3");
}

</style>
