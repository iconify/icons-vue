<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j0a22jbhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:baby-bottle-sharp" /></template>
<style>
.j0a22jbhx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 6.5v-3h3v3ZM8 6.5h8V9H8zm.75 4.75h6.5v10h-6.5zm0 3.25h2.5m-2.5 3.25h2.5");
}

</style>
