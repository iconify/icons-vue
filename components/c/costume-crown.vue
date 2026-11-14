<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c8krcvbyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:costume-crown" /></template>
<style>
.c8krcvbyi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.982 19.55l-1.6-11.388l5.152 4.325l2.492-7.419l4.44 6.445l3.76-5.578l1.601 11.388Zm-.487-3.466l15.845-2.227");
}

</style>
