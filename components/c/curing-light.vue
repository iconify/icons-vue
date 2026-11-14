<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o7i9lrvjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:curing-light" /></template>
<style>
.o7i9lrvjg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 11.75L12.25 3h3A1.75 1.75 0 0 1 17 4.75v3.5h-3.5v-1.5L6 14.25Zm11.75 3.75c-1-1-4.25-1.25-4.25 1.75c0 1.5.75 2.25 1.25 3.25l.5 1h1l1.5-2l1.5 2h1l.5-1c.5-1 1.25-1.75 1.25-3.25c0-3-3.25-2.75-4.25-1.75Zm0-4.75v1.5M12.75 11L12 12.25m6-1.5l.75 1.25");
}

</style>
