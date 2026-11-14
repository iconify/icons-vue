<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqeblzwhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hand-soap-pump" /></template>
<style>
.cqeblzwhb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 10h10v11.5H4Zm3-3h4v3H7Zm2 0V3.5m-3 0h13v2M19 9s2 2.5 2 3.75a2 2 0 0 1-4 0C17 11.5 19 9 19 9Z");
}

</style>
