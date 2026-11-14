<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="he3xgryho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:carol-singer" /></template>
<style>
.he3xgryho {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 21c-2.5-1.5-6-1.75-9-1.25V12.5c3-.5 6.5-.25 9 1.25c2.5-1.5 6-1.75 9-1.25v7.25c-3-.5-6.5-.25-9 1.25Zm0-7.25V21M9.25 8a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm3.5 0V2.5m0 0q1.75.75 3.25 2.75");
}

</style>
