<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ho6le9ryx"/><path class="k7vzmkvfh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:banner-alert" /></template>
<style>
.ho6le9ryx {
  d: path("M3 3h18M4.5 3h15v18L12 17l-7.5 4Z");
}

.k7vzmkvfh {
  d: path("m12 6l4.5 8h-9Zm0 3v2m0 1.75h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
