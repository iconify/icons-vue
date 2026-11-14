<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g9u1ccc1z"/><path class="h93dddxmq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dashiki-shirt" /></template>
<style>
.g9u1ccc1z {
  d: path("M8 3L2.5 6.5L4 11l1.5-.75V21h13V10.25L20 11l1.5-4.5L16 3a4 3 0 0 1-8 0Z");
}

.h93dddxmq {
  d: path("m8.5 13l1.75-1.75L12 13l1.75-1.75L15.5 13");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
