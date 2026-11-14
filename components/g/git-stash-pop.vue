<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iihgooxri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:git-stash-pop" /></template>
<style>
.iihgooxri {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 12v7.5a2 2 0 0 0 2 2h11a2 2 0 0 0 2-2V12ZM2.779 9.543l6.553-4.589l1.721 2.457L4.5 12ZM17 4v5.25M14.5 6.5L17 4l2.5 2.5");
}

</style>
