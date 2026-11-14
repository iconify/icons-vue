<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="khv4wov4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:booklet" /></template>
<style>
.khv4wov4o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.864 4.966l6 1.5A1.5 1.5 0 0 1 12 7.921v11.658a1.5 1.5 0 0 1-1.864 1.455l-6-1.5A1.5 1.5 0 0 1 3 18.079V6.421a1.5 1.5 0 0 1 1.864-1.455m8.272 1.5l6-1.5A1.5 1.5 0 0 1 21 6.421v11.658a1.5 1.5 0 0 1-1.136 1.455l-6 1.5A1.5 1.5 0 0 1 12 19.579V7.921a1.5 1.5 0 0 1 1.136-1.455M6 9.25L9 10m6 0l3-.75");
}

</style>
