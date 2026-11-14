<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a_stni5md"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:job-fair" /></template>
<style>
.a_stni5md {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 9.5l2-5h14l2 5Zm1.5 0v12m15-12v12M4.5 14h15M9.75 4.5L9 9.5m5.25-5l.75 5m-7.5 7.25h9v4.75h-9Z");
}

</style>
