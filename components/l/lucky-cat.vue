<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b25yinbvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lucky-cat" /></template>
<style>
.b25yinbvf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 10V2.5L12 5h3l3.5-2.5V10c0 1.5 1.5 3 1.5 6v5.5H6.5v-5H4A1.5 1.5 0 0 1 2.5 15V9a1.5 1.5 0 0 1 3 0v3.5c1 0 3-1 3-2.5Zm3-2.5h.01m3.99 0h.01");
}

</style>
