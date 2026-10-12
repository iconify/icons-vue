<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y52uh2bea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cactus-sharp" /></template>
<style>
.y52uh2bea {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 21.25v-16a2.5 2.5 0 0 1 5 0v16Zm0-6.5H5.25V9m9.25 3h4.25V7m-12 14.25h10.5");
}

</style>
