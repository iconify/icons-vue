<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="z6zf6db1g"/><path class="d7z7pnqyw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:home-alt" /></template>
<style>
.d7z7pnqyw {
  d: path("M5 9.5V19a1 1 0 0 0 1 1h12a1 1 0 0 0 1-1V9.5M12 15v5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z6zf6db1g {
  d: path("m2.5 11.5l9.5-8l9.5 8");
}

</style>
