<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wdgrxq5ay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:camp-stool" /></template>
<style>
.wdgrxq5ay {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 5.5a8.5 3 0 1 0 17 0a8.5 3 0 1 0-17 0ZM7 7.75L3.5 21.5M17 7.75l3.5 13.75M12 8.5v13");
}

</style>
