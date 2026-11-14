<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ssqzbcc6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:guest-checkout" /></template>
<style>
.ssqzbcc6m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.237 21H3.5c-.6 0-1-.4-1-1c0-2.5 2.5-4.5 5.5-4.5c1.187 0 2.297.313 3.203.847M4.25 8.25a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0ZM14 14.5h8v7h-8Zm0 2.75h8");
}

</style>
