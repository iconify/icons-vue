<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mua3j_7sw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chick-hatching" /></template>
<style>
.mua3j_7sw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.5 13.5l2.25 2.25L9 13.5l3 2.25l3-2.25l2.25 2.25l2.25-2.25c0 5-3 8-7.5 8s-7.5-3-7.5-8Zm4.5 0V11a3 3 0 0 1 6 0v2.5M7.5 5.25a4.5 3.25 0 0 1 9 0ZM15 10.5l2.5.75L15 12Zm-3.75.25h.01");
}

</style>
