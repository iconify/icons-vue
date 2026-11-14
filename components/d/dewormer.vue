<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hyinukb4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dewormer" /></template>
<style>
.hyinukb4n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.282 12.768l8.486-8.486a1.5 1.5 0 0 1 2.121 0l2.829 2.829a1.5 1.5 0 0 1 0 2.121l-8.486 8.486a1.5 1.5 0 0 1-2.121 0l-2.829-2.829a1.5 1.5 0 0 1 0-2.121Zm4.243-4.243l4.95 4.95M15.25 19.5c.75-3 2.75-3 3.25-1s2.5 2 3.25-1");
}

</style>
