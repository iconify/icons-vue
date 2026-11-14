<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dgw5-l3ud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dolphin" /></template>
<style>
.dgw5-l3ud {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 16.75c2.25-5.5 5-8.25 7.5-9.25L11.25 4l4.25 3.25C18 7.5 19.75 9 21.5 11l-3 .75C14 11.25 9.75 13.5 6.25 18l.25 2.75l-1.75-1.5H3Z");
}

</style>
