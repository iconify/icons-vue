<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yy3mofwlr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:khanda" /></template>
<style>
.yy3mofwlr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 2.75l1.5 2.5v9h-3v-9Zm-3.25 11.5h6.5m-3.25 0v4.5m3.25 2.5C7 20.5 2.25 14.5 3.75 4.5m5 16.75c8.25-.75 13-6.75 11.5-16.75");
}

</style>
