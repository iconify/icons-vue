<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qwzom8bte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:flip-horizontal-sharp" /></template>
<style>
.qwzom8bte {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3.25v2.5m0 2.5v2.5m0 2.5v2.5m0 2.5v2.5M9 8.575v8.05H3l.65-1.01l4.7-7.23l.65-1.01zm6 0v8.05h6l-.65-1.01l-4.7-7.23l-.65-1.01z");
}

</style>
