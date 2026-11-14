<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w2yy2f43b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fog-machine-stage" /></template>
<style>
.w2yy2f43b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 14h18v7H3Zm6.5 0L8 10.5h8L14.5 14m-8 3.5H11M9 7.75C7.5 6 6 7.5 4.5 4.5M12 7.75C10.5 6 13.5 5 12 3m3 4.75C16.5 6 18 7.5 19.5 4.5");
}

</style>
