<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ap7v8cdoa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chef-uniform" /></template>
<style>
.ap7v8cdoa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 4.5L4.5 6l-2 7.5l2.5.75L7 9.5v12h10v-12l2 4.75l2.5-.75l-2-7.5l-4-1.5Zm.75 0v-2h5.5v2M10 10h.01M14 10h.01M10 15h.01M14 15h.01");
}

</style>
