<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hy9zjp-ua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:aspergillum" /></template>
<style>
.hy9zjp-ua {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18.328 5.172za3 3 0 0 1 0 4.242l-1.414 1.414a3 3 0 0 1-4.242 0a3 3 0 0 1 0-4.242l1.414-1.414a3 3 0 0 1 4.242 0M12.75 10.75L4.5 19M15 17h.01m3.49-.5h.01m1.99-3h.01");
}

</style>
