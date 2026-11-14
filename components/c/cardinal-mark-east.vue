<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ia7b5nb3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cardinal-mark-east" /></template>
<style>
.ia7b5nb3u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 2.5l4 3.75L12 10L8 6.25Zm0 7.5v2m-5 9l1.75-9h6.5L17 21ZM8 6.25h8M8 16.5h8");
}

</style>
