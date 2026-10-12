<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eom7thbnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bulldog-clip-sharp" /></template>
<style>
.eom7thbnc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 11.5V7h3.5v4.5m3 0V7H17v4.5m-8.5 0H17l.39 1.45l.97 3.6l.39 1.45H5.25l.39-1.45l.97-3.6L7 11.5zM8 18v3.25h8V18");
}

</style>
