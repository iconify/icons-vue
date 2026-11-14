<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b17hg02us"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:campaign-edit" /></template>
<style>
.b17hg02us {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 6.5h4.5l8.5-4v11.25L7.5 10H3ZM5.5 10l1.25 5M15 21v-2.25l4.25-4.25l2.25 2.25L17.25 21Z");
}

</style>
