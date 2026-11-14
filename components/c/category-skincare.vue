<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w2-mqlw1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:category-skincare" /></template>
<style>
.w2-mqlw1u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 12h17v2.5h-17ZM5 14.5v4q0 3 2.5 3h9q2.5 0 2.5-3v-4M8 12c-1-3.5.5-4.5 4-4.5s5 1 4 4.5M9.25 7.5C9.25 5 10.5 4.25 12 4.25s2.75.75 2.75 3.25M12 4.25c0-1.25 1-1.75 2-1.5");
}

</style>
