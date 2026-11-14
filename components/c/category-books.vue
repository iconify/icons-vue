<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ste3ksb6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:category-books" /></template>
<style>
.ste3ksb6h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 3.5h10.5A1.75 1.75 0 0 1 20 5.25v2A1.75 1.75 0 0 1 18.25 9H7.75A1.75 1.75 0 0 1 6 7.25v-2A1.75 1.75 0 0 1 7.75 3.5m-3 5.5h11.5A1.75 1.75 0 0 1 18 10.75v2.5A1.75 1.75 0 0 1 16.25 15H4.75A1.75 1.75 0 0 1 3 13.25v-2.5A1.75 1.75 0 0 1 4.75 9m1.5 6h13.5a1.75 1.75 0 0 1 1.75 1.75v3a1.75 1.75 0 0 1-1.75 1.75H6.25a1.75 1.75 0 0 1-1.75-1.75v-3A1.75 1.75 0 0 1 6.25 15M8.5 3.5V9M16 6.25h4M15.5 9v6M3 12h4m0 3v6.5m10.5-3.25h4");
}

</style>
