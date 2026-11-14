<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l29rkab1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:group-discussion" /></template>
<style>
.l29rkab1v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 11.75a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0ZM3 21c0-2.5 1.75-3.75 4-3.75s4 1.25 4 3.75m3.25-9.25a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0ZM13 21c0-2.5 1.75-3.75 4-3.75s4 1.25 4 3.75M9.5 2.5h5A1.5 1.5 0 0 1 16 4v2a1.5 1.5 0 0 1-1.5 1.5H13L12 9l-1-1.5H9.5A1.5 1.5 0 0 1 8 6V4a1.5 1.5 0 0 1 1.5-1.5Z");
}

</style>
