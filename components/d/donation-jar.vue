<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="aqxsg-6og"/><path class="s4_fdzbxl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:donation-jar" /></template>
<style>
.aqxsg-6og {
  d: path("M5 2.5h14V6H5ZM6.5 6l-1 2.5V19a2 2 0 0 0 2 2h9a2 2 0 0 0 2-2V8.5l-1-2.5");
}

.s4_fdzbxl {
  d: path("M8.5 12h7v3h-7Zm0 3h7v3h-7Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
