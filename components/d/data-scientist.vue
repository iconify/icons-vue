<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="irmpbhb-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:data-scientist" /></template>
<style>
.irmpbhb-s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.572 21H4.5c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5c.789 0 1.543.078 2.249.225M7 7.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm10 6.75h2V17l2.5 4.5h-7L17 17Zm-1 0h4");
}

</style>
