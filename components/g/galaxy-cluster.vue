<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k3qu51izt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:galaxy-cluster" /></template>
<style>
.k3qu51izt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 6.5a4.5 2.75 0 1 0 9 0a4.5 2.75 0 1 0-9 0Zm9 4.5a4.5 2.75 0 1 0 9 0a4.5 2.75 0 1 0-9 0Zm-8.5 6.5a4.5 2.75 0 1 0 9 0a4.5 2.75 0 1 0-9 0Zm4-11h.01M16.5 11h.01M8 17.5h.01");
}

</style>
