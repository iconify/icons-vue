<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v4oiscbhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:breadcrumbs" /></template>
<style>
.v4oiscbhc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 8h1.75q.75 0 1.17.62l1.91 2.76q.42.62 0 1.24l-1.91 2.76Q6 16 5.25 16H3.5q-.75 0-.33-.62l1.91-2.76q.42-.62 0-1.24L3.17 8.62Q2.75 8 3.5 8m6.25 0h1.75q.75 0 1.17.62l1.91 2.76q.42.62 0 1.24l-1.91 2.76q-.42.62-1.17.62H9.75q-.75 0-.33-.62l1.91-2.76q.42-.62 0-1.24L9.42 8.62Q9 8 9.75 8M16 8h1.75q.75 0 1.17.62l1.91 2.76q.42.62 0 1.24l-1.91 2.76q-.42.62-1.17.62H16q-.75 0-.33-.62l1.91-2.76q.42-.62 0-1.24l-1.91-2.76Q15.25 8 16 8");
}

</style>
