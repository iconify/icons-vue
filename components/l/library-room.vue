<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uu7fz9bau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:library-room" /></template>
<style>
.uu7fz9bau {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 19h19m-17 0v2.5m15-2.5v2.5M4 19V9h3v10m0 0V6h3v13m0 0v-8h2.75v8m1.5 0L18 8l2.75 1L17 19");
}

</style>
