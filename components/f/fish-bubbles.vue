<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s1gyd4llm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fish-bubbles" /></template>
<style>
.s1gyd4llm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M21 15c-3-5-10.5-5-13.5 0L3 11v8l4.5-4c3 5 10.5 5 13.5 0Zm-6.5-8a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM19 3h.01M17.5 14.5h.01");
}

</style>
