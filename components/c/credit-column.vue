<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dtg1k2boz"/><path class="ahtra4brk"/><path class="iqd8hj7pe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:credit-column" /></template>
<style>
.ahtra4brk {
  fill: currentColor;
  d: path("M13.5 5.5h3.25v13H13.5Z");
}

.dtg1k2boz {
  d: path("M4.5 2.5h15v19h-15Zm6.25 0v19");
}

.iqd8hj7pe {
  d: path("M4.5 9h6.25M4.5 15h6.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
