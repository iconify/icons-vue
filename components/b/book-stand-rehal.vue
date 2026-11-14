<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qy5kq4bll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:book-stand-rehal" /></template>
<style>
.qy5kq4bll {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 5.5C10 4 6.5 3.5 3 4v7.5c3.5-.5 7 0 9 1.5c2-1.5 5.5-2 9-1.5V4c-3.5-.5-7 0-9 1.5m0 0V13m-5.5-1.5l11 9.5m0-9.5L6.5 21");
}

</style>
