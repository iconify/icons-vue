<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nhaxj7b0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:agenda-sheet-sharp" /></template>
<style>
.nhaxj7b0v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 3.75h14.5v17.5H4.75zm3.75-1v2.5m3.5-2.5v2.5m3.5-2.5v2.5M8.25 10h7.5m-7.5 3.5h7.5M8.25 17h4.5");
}

</style>
