<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wqil0bc7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:check-valve" /></template>
<style>
.wqil0bc7i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 4v12m17-12v12M3.5 6h17m-17 8h17M12 6l2 4.25M7 18.5h10m-2.25-2.25L17 18.5l-2.25 2.25");
}

</style>
