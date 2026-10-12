<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="szqd1jbbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:camshaft-sharp" /></template>
<style>
.szqd1jbbp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 12H4.5m3 0h3m3 0h3m3 0h1.75M4 9.5a2 2 0 0 1 4 0c0 2-1 4-2 4s-2-2-2-4Zm6 5a2 2 0 0 0 4 0c0-2-1-4-2-4s-2 2-2 4Zm6-5a2 2 0 0 1 4 0c0 2-1 4-2 4s-2-2-2-4Z");
}

</style>
