<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n0yfykb9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:breast-pump-sharp" /></template>
<style>
.n0yfykb9l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.27 10.39L3.23 8.11l-.48-.36v8.5l.48-.36l3.04-2.28l.48-.36v-2.5zM9.75 8.5h6.5v12.75h-6.5zm0 4h6.5M13 8.5V3.75h7.25");
}

</style>
