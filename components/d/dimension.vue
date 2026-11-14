<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zf-djx3xo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dimension" /></template>
<style>
.zf-djx3xo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 15.75H15l3.5 2.75l-3.5 2.75H3.5Zm11.25 2.75h.01m-9.51-4.25l6.75-4l4.5.75l-1.25 3.25m-2-1.25h.01M3 14l3.75-6.75L11 5.5l.5 3.5m-2.25-.25h.01");
}

</style>
