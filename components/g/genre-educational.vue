<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lg_wrqbjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:genre-educational" /></template>
<style>
.lg_wrqbjq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 13.5c-2.5-1.5-6-1.75-9-1V20c3-.75 6.5-.5 9 1c2.5-1.5 6-1.75 9-1v-7.5c-3-.75-6.5-.5-9 1Zm0 0V21M4 6l8-3l8 3l-8 3Zm16 0v3.5");
}

</style>
