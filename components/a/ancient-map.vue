<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="az9oq4bnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ancient-map" /></template>
<style>
.az9oq4bnx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 3h17v3.5h-17Zm0 14.5h17V21h-17Zm2-11v11m13-11v11m-10-3l2-2l1.75.5M14 8.75l2 2m0-2l-2 2");
}

</style>
