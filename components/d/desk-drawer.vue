<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jqt38bcoh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:desk-drawer" /></template>
<style>
.jqt38bcoh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4.5h19m-17 0V8m15-3.5V8m-17 0h19v5.5h-19Zm2 5.5v7h15v-7m-10-2.75h5M9.5 17h5");
}

</style>
