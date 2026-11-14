<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ql40nyb6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:game-controller-x" /></template>
<style>
.ql40nyb6e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 6.5h9c2.5 0 4 1.5 4.5 4l.75 5c.25 2-1 3.25-2.5 3.25c-1.25 0-2-.75-2.75-1.75l-1-1.5h-7l-1 1.5c-.75 1-1.5 1.75-2.75 1.75c-1.5 0-2.75-1.25-2.5-3.25l.75-5c.5-2.5 2-4 4.5-4Zm2.5 3l4 4m0-4l-4 4");
}

</style>
