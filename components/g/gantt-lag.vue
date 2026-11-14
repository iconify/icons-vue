<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yv2lgc-9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gantt-lag" /></template>
<style>
.yv2lgc-9t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3H10v4H2.5ZM14 17h7.5v4H14Zm-6.5-5h9M9.75 9.75L7.5 12l2.25 2.25m4.5-4.5L16.5 12l-2.25 2.25");
}

</style>
