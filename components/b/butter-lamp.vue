<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4mkbxs-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:butter-lamp" /></template>
<style>
.l4mkbxs-v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 12h16c0 4-3.5 6-8 6s-8-2-8-6Zm5 9.5l1.5-3.5h3l1.5 3.5Zm3-19q4.5 4.875 0 6.75q-4.5-1.875 0-6.75Z");
}

</style>
