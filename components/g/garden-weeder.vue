<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w8o4k_b4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:garden-weeder" /></template>
<style>
.w8o4k_b4i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.268 12.904l2.828 2.828l-6.364 6.364l-2.828-2.828ZM9.75 14.25l3.75-3.75m0 0l2-2L17 3m-1.5 5.5L21 7");
}

</style>
