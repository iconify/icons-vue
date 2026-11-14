<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hm1cn3sws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:leaf-maple" /></template>
<style>
.hm1cn3sws {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 2.5l2 2.75l2-.75l-1 4.25l6-2.25l-2 4l1.5 1l-4 3l.75 2L12 16l-5.25.5l.75-2l-4-3l1.5-1l-2-4l6 2.25L8 4.5l2 .75Zm0 7.5v11.5");
}

</style>
