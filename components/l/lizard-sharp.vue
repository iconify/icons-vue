<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="keup7nb0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lizard-sharp" /></template>
<style>
.keup7nb0g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75c.75 0 2.5 2 2.5 3.5v2h-5v-2c0-1.5 1.75-3.5 2.5-3.5ZM11 6.5h.01m1.99 0h.01M10 8.75h4V16h-4zm0 1.5H8l-.75-2m6.75 2h2l.75-2m-6.75 6H8l-.75 2m6.75-2h2l.75 2m-9.5-8L6 7.75m1.25.5L7 7m.25 1.25l.75-.5m8.75.5l1.25-.5m-1.25.5L17 7m-.25 1.25l-.75-.5m-8.75 8.5l-1.25.5m1.25-.5L7 17.5m.25-1.25l.75.5m8.75-.5l1.25.5m-1.25-.5L17 17.5m-.25-1.25l-.75.5M12 16c0 1.5 2 1.75 2 3.25v2h-2.5");
}

</style>
