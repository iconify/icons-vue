<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wyrfyub-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:home-office-stipend" /></template>
<style>
.wyrfyub-f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.5 11.5h-9v-9h14v1.8m-7 7.2v3m-2.25 0h4.5M2 17.25h20m-18 0v4.25m16-4.25v4.25m-5.75-11a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm3.5-1.25v2.5");
}

</style>
