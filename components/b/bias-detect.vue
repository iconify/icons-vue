<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ux796fb4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bias-detect" /></template>
<style>
.ux796fb4k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4 4.5l16 4m-8-2v13m-4 0h8M4 4.5l-2 6a2 2 0 0 0 4 0Zm16 4l-2 6a2 2 0 0 0 4 0Z");
}

</style>
