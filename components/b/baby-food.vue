<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="br0i09bkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:baby-food" /></template>
<style>
.br0i09bkj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 7.75h11.5v13H3Zm1-3.5h9.5v3.5H4ZM3 12h11.5M3 16.5h11.5m3 4.25l2-10.5M18 7a1.75 3 0 1 0 3.5 0A1.75 3 0 1 0 18 7Z");
}

</style>
