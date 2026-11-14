<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iyyo_6jgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:job-family" /></template>
<style>
.iyyo_6jgv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 21.5V8m0 8.5L7.5 12m4.5 2l4.5-4.5M9 21.5h6m-11-11a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM9.5 5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM16 8a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

</style>
