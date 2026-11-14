<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="busunby6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hockey-goalie" /></template>
<style>
.busunby6z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5c5.5 0 7 3.5 7 7.5c0 5.5-3 11.5-7 11.5s-7-6-7-11.5c0-4 1.5-7.5 7-7.5Zm-7 8h14M5.75 15h12.5M12 10.5v11");
}

</style>
