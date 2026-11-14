<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qtzk7i3ea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:go-live" /></template>
<style>
.qtzk7i3ea {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM8.465 7.787a5.5 5.5 0 0 1 7.07 0M5.894 4.723a9.5 9.5 0 0 1 12.212 0m-2.571 11.49a5.5 5.5 0 0 1-7.07 0m9.641 3.064a9.5 9.5 0 0 1-12.212 0");
}

</style>
