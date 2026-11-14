<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g9khv1hcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:jigger" /></template>
<style>
.g9khv1hcg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.864 2.5h6.272a1.5 1.5 0 0 1 1.358 2.139l-2.783 5.913a1.5 1.5 0 0 0-.114.933l1.544 7.721A1.5 1.5 0 0 1 13.67 21h-3.34a1.5 1.5 0 0 1-1.471-1.794l1.544-7.721a1.5 1.5 0 0 0-.114-.933L7.506 4.639A1.5 1.5 0 0 1 8.864 2.5M9.75 11h4.5m-6-4.5h7.5");
}

</style>
