<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="vspbepdvt"/><path class="ysz2qqeub"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lab-coat-sharp" /></template>
<style>
.vspbepdvt {
  d: path("M8.25 3.25L12 8l3.75-4.75L19.4 4.9l.849.408l.001.942v15H3.75v-15l.001-.942L4.6 4.9Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ysz2qqeub {
  d: path("M8.25 3.25L12 8l-2.25 3.25L7 6.5Zm7.5 0L12 8l2.25 3.25L17 6.5ZM12 12.5v6.75m3-4h2.25");
}

</style>
