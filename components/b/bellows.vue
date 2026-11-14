<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qhyeqbcmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bellows" /></template>
<style>
.qhyeqbcmq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4.5h3v15h-3Zm16 0h3v15h-3ZM5.5 7l2.25 2.5L10 7l2 2.5L14 7l2.25 2.5L18.5 7m-13 10l2.25-2.5L10 17l2-2.5l2 2.5l2.25-2.5L18.5 17");
}

</style>
