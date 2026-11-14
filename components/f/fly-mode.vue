<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d5zyumbtn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fly-mode" /></template>
<style>
.d5zyumbtn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 21V3M8.5 6.5L12 3l3.5 3.5m-3.5 5c-3.5 0-7-.75-9.5-3c0 3 1.25 4.5 3.5 5c.25 1.75 2.25 3 6 3m0-5c3.5 0 7-.75 9.5-3c0 3-1.25 4.5-3.5 5c-.25 1.75-2.25 3-6 3");
}

</style>
