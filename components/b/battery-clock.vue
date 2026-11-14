<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x89iitb4u"/><path class="a6cpk6bfi"/><path class="r87sa_1ne"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:battery-clock" /></template>
<style>
.a6cpk6bfi {
  d: path("M6.75 12a4 4 0 1 0 8 0a4 4 0 1 0-8 0Z");
}

.r87sa_1ne {
  d: path("M10.75 10v2l1.5 1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x89iitb4u {
  d: path("M2.5 5H19v14H2.5ZM19 9.5h1.5a1 1 0 0 1 1 1v3a1 1 0 0 1-1 1H19");
}

</style>
