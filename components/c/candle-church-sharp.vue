<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lit-zq59u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:candle-church-sharp" /></template>
<style>
.lit-zq59u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75C13.25 4 14 5 14 6a2 2 0 0 1-4 0c0-1 .75-2 2-3.25ZM7.75 11h8.5v10.25h-8.5zM12 13.75v5m-2-3h4");
}

</style>
