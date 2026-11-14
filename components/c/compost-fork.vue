<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="spev8tb-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:compost-fork" /></template>
<style>
.spev8tb-u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m15.005 2.631l-4.242 4.242l6.364 6.364l4.242-4.242m-4.242-4.243l-4.243 4.243m6.364-2.122l-4.243 4.243m-1.06-1.061l-5.834 5.834m-1.768-1.768l3.536 3.536l-2.829 2.828l-3.535-3.535Z");
}

</style>
