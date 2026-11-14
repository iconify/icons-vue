<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="adhcgsbnq"/><path class="ju9h5i31x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hoverboard" /></template>
<style>
.adhcgsbnq {
  d: path("M2.5 8.25h19v3.5h-19Z");
}

.ju9h5i31x {
  d: path("M2.5 14.75a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm13 0a3 3 0 1 0 6 0a3 3 0 1 0-6 0ZM5 5.5h4.5m5 0H19");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
