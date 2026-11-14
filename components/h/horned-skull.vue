<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cef0rvbvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:horned-skull" /></template>
<style>
.cef0rvbvd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 8c0-1.5 1-2.5 2.5-2.5h7C17 5.5 18 6.5 18 8v3.5l-2.75 8.25c-.25 1-1 1.75-2 1.75h-2.5c-1 0-1.75-.75-2-1.75L6 11.5Zm0 0C3.5 8 2.25 6.5 2.5 3.5M18 8c2.5 0 3.75-1.5 3.5-4.5m-12 7.25h.01m4.99 0h.01");
}

</style>
