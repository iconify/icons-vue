<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="hw1nvuqao"/><path class="ldbi5_j5f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:humidifier-sharp" /></template>
<style>
.hw1nvuqao {
  d: path("M5.75 9.75h12.5v11.5H5.75z");
}

.ldbi5_j5f {
  d: path("m8.5 15.25l1.75-1.05L12 15.25l1.75 1.05l1.75-1.05m-6-7.75c-.75-.75.75-1.25 0-2s.75-1.25 0-2m5 4c-.75-.75.75-1.25 0-2s.75-1.25 0-2");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
