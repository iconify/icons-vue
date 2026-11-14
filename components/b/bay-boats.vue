<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rruu6gbsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bay-boats" /></template>
<style>
.rruu6gbsb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 13.75h17L18 17H6ZM12 11v2.75M12 3v8h6.5c0-4-3-6.5-6.5-8ZM2.5 20.5q4.75-1.5 9.5 0t9.5 0");
}

</style>
