<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-v8tbpau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:airport-sharp" /></template>
<style>
.r-v8tbpau {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 4.75h11.5l-.34.94l-1.32 3.62l-.34.94h-8.5l-.34-.94l-1.32-3.62l-.34-.94zm2 2.75h6.5m-5.5 2.75h4.5L15 20.5H9Zm-6 10.25h16.5M12 4.75v-2");
}

</style>
