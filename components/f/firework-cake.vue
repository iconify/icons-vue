<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eraspxbaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:firework-cake" /></template>
<style>
.eraspxbaa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 13h16v8.5H4Zm5.25 0v8.5m5.5-8.5v8.5M12 4.5V2.25M12 8v2.25m-1.75-4H8m5.75 0H16M10.75 5l-1.5-1.5m4 1.5l1.5-1.5m-4 4L9.25 9m4-1.5l1.5 1.5");
}

</style>
