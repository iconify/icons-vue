<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="zuw80qb6p"/><circle class="o5vk1es1c"/><path class="o6qu17bqq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gothic-window-sharp" /></template>
<style>
.o5vk1es1c {
  cx: 12px;
  cy: 7.5px;
  r: 1.25px;
}

.o6qu17bqq {
  d: path("M8 21.25V13.5l2-1.25l2 1.25V16v-2.5l2-1.25l2 1.25v7.75M12 16v5.25");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zuw80qb6p {
  d: path("M5.5 21.25V11.5C5.5 7 8.5 4 12 2.75C15.5 4 18.5 7 18.5 11.5v9.75Z");
}

</style>
