<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ep07rigkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chi-square" /></template>
<style>
.ep07rigkn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4 9l9 11m0-11L4 20M16.5 4.5a1.75 1.75 0 0 1 3.5.25c0 1.5-3.5 2.25-3.5 3.75h4");
}

</style>
