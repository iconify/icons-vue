<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="geh18sbrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:friction" /></template>
<style>
.geh18sbrk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 9h11v7h-11ZM3 20.5L5 19l2 1.5L9 19l2 1.5l2-1.5l2 1.5l2-1.5l2 1.5l2-1.5M18 4.25H6m2-2l-2 2l2 2");
}

</style>
