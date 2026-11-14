<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bh68182jg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chat-bubble-heart-pair" /></template>
<style>
.bh68182jg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 13S3 9.75 3 6.25c0-1.65 1.25-3 2.75-3C7 3.25 8 4 8.5 5C9 4 10 3.25 11.25 3.25c1.5 0 2.75 1.35 2.75 3C14 9.75 8.5 13 8.5 13Zm5.5.75h4.5a2.5 2.5 0 0 1 2.5 2.5V21l-3-2h-4a2.5 2.5 0 0 1-2.5-2.5v-.25a2.5 2.5 0 0 1 2.5-2.5Z");
}

</style>
