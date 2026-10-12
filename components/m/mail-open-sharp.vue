<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="lxp8i07mk"/><path class="p-hn58bia"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mail-open-sharp" /></template>
<style>
.lxp8i07mk {
  d: path("m2.75 10.25l.002-1.364L3.9 8.15l6.75-4.4L12 2.884l1.35.866l6.75 4.4l1.148.736l.002 1.364v10H2.75v-2.5Z");
}

.p-hn58bia {
  d: path("m3.5 9.25l7.1 4.6l1.4.906l1.4-.906l7.1-4.6");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
