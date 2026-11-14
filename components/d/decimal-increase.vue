<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gzagn8cjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:decimal-increase" /></template>
<style>
.gzagn8cjt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 17.5h.01M7.5 14a2.5 3.5 0 1 0 5 0a2.5 3.5 0 1 0-5 0Zm7 0a2.5 3.5 0 1 0 5 0a2.5 3.5 0 1 0-5 0ZM4 6h16m-2.5-2.5L20 6l-2.5 2.5");
}

</style>
