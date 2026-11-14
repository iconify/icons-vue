<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a5vj0ibqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bowling-hotel" /></template>
<style>
.a5vj0ibqr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 21c-1-3.5-.5-7 1-9.5c.5-1 0-2-.25-3C6.25 6.5 7 3 9 3s2.75 3.5 2.25 5.5c-.25 1-.75 2-.25 3c1.5 2.5 2 6 1 9.5Zm8.75-3.25a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0ZM7 9.5h4");
}

</style>
