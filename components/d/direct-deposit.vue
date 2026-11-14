<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lxzw3tynn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:direct-deposit" /></template>
<style>
.lxzw3tynn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 9L12 3.5L20.5 9Zm0 11.5h17M6 11.75v6m12-6v6m-6-6v6M9.25 15L12 17.75L14.75 15");
}

</style>
