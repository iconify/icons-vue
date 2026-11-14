<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tix_u-_qu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:crimping" /></template>
<style>
.tix_u-_qu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 9.5h7v5h-7Zm-6 2.5h6m8 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm-1 0h1M12 2.5v4m-1.75-1.75L12 6.5l1.75-1.75M12 21.5v-4m-1.75 1.75L12 17.5l1.75 1.75");
}

</style>
