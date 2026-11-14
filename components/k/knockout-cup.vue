<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j9mvkybqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:knockout-cup" /></template>
<style>
.j9mvkybqg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.5 3.5h9V8a4.5 4.5 0 0 1-9 0Zm4.5 9V17m-3.5 0h7v3.5h-7ZM2.5 5H6v8H2.5M6 9h2.75");
}

</style>
