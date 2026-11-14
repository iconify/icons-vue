<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vssgtrbkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:commute-time" /></template>
<style>
.vssgtrbkg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15 2.5h6.5v10H15Zm3.25 3h.01M18.25 9h.01M3 21.5c2-4.5 7-6 12.5-7m-2.5 7c1-3.5 3.5-6 6.5-7m-11 5l1.75-1.5");
}

</style>
