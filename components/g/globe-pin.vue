<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o3qmgs4om"/><path class="fyz_yjbhu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:globe-pin" /></template>
<style>
.fyz_yjbhu {
  d: path("M8 12c0-3.8 1.8-7.2 4-9.5c2.2 2.3 4 5.7 4 9.5m2 9.5s-3-2.5-3-4.25a3 3 0 0 1 6 0c0 1.75-3 4.25-3 4.25Z");
}

.o3qmgs4om {
  d: path("M21.5 12h-7.25a2 2 0 0 0-2 2v7.5A9.5 9.5 0 1 1 21.5 12Zm-19 0h9.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
