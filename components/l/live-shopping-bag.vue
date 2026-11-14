<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tysgqtbca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:live-shopping-bag" /></template>
<style>
.tysgqtbca {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.923 8.5h5.654a2.625 2.625 0 0 1 2.616 2.416l.58 7.25A2.625 2.625 0 0 1 13.157 21H6.343a2.625 2.625 0 0 1-2.616-2.834l.58-7.25A2.625 2.625 0 0 1 6.923 8.5M7 8.5V7a2.75 2.75 0 0 1 5.5 0v1.5M15 5a3.5 3.5 0 0 1 3.5 3.5M15 2.25a6.25 6.25 0 0 1 6.25 6.25");
}

</style>
