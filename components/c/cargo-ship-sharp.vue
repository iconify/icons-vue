<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ih4gafgxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cargo-ship-sharp" /></template>
<style>
.ih4gafgxi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 13.25h18.5l-2 5.25l-.367 1.23l-1.283.02H6.4l-1.283-.02l-.367-1.23Zm2-7.5h5.5v4.5h-5.5zm8.5 1h6v3.5h-6z");
}

</style>
