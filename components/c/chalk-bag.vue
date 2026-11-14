<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n58ju_blk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chalk-bag" /></template>
<style>
.n58ju_blk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 8h6c3.5 2.5 5 5.5 5 8c0 3.5-3 5.5-8 5.5s-8-2-8-5.5c0-2.5 1.5-5.5 5-8Zm0 0L7 4.5h10L15 8Zm1-3.5c0-2.75 4-2.75 4 0");
}

</style>
