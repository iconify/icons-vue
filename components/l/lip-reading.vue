<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hbyagibme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lip-reading" /></template>
<style>
.hbyagibme {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 6.5c1.5-2 3.5-3 5.5-3s4 1 5.5 3c-1.5 2-3.5 3-5.5 3s-4-1-5.5-3m-2 9.5c2.5-3 5-3 7.5-1.75C14.5 13 17 13 19.5 16c-2.5 3.5-5 4.5-7.5 4.5s-5-1-7.5-4.5M12 6.5h.01M4.5 16h15");
}

</style>
