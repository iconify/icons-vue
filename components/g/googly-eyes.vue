<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zl6ihjb8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:googly-eyes" /></template>
<style>
.zl6ihjb8e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 8.5a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0Zm9.75 6.75a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0ZM8.5 10h.01m6.74 3.75h.01");
}

</style>
