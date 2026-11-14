<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rfi7yj1wq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:keep-middle" /></template>
<style>
.rfi7yj1wq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 20.5V4M9.25 6.75L12 4l2.75 2.75M3 21l1.5-6.5m1-4L7 4m14 17l-1.5-6.5m-1-4L17 4");
}

</style>
