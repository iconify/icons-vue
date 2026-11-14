<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jy3lg-b0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dhak-drum" /></template>
<style>
.jy3lg-b0i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 10h11q2.5 5.75 0 11.5h-11Q4 15.75 6.5 10ZM8 2.5l7.5 4.75M16 2.5L8.5 7.25");
}

</style>
