<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oseykm-bn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hinge" /></template>
<style>
.oseykm-bn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 4h7v16h-7Zm10 0h7v16h-7Zm-3-1h3v18h-3ZM6.75 7.5h.01m-.01 9h.01m10.49-9h.01m-.01 9h.01");
}

</style>
