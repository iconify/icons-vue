<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dzm2g_erw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:beta-particle" /></template>
<style>
.dzm2g_erw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 12a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0ZM3 9.5h6.25M5 14.5h4.25");
}

</style>
