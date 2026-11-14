<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hfb9w6b8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:desktop-off" /></template>
<style>
.hfb9w6b8h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.4 2.5h15.1V15h-2.6m-7.8 0H2.5V6.4m15.1 15.1H3.5v-3h11.1M3.5 3.5l17 17");
}

</style>
