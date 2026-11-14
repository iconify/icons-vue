<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="s0qiigbxb"/><path class="oh-560cgq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:directions-walk" /></template>
<style>
.oh-560cgq {
  d: path("M8 12.5L9.5 9l2.5-.5l2.5 3l2.5 1");
}

.s0qiigbxb {
  d: path("M11.5 4a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm.5 4.5l-1.5 6l3 3V21m-3-6.5L8 21");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
