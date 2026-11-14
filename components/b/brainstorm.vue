<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="znoudjbxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:brainstorm" /></template>
<style>
.znoudjbxe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 21.5V19c-1.5-1.25-2.5-2.75-2.5-4.75c0-2.5 2.25-4.25 5-4.25s4.75 1.75 4.75 4.25l1.25 2.5c.1.35-.1.75-.5.75h-.75v1.25c0 .65-.5 1.25-1.25 1.25h-1v1.5m4.75-10v-1c-1.5-.9-2.25-2.4-2.25-4c0-2.25 1.75-4 4-4s4 1.75 4 4c0 1.6-.75 3.1-2.25 4v1Zm.5 2.75h2.5");
}

</style>
