<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ua6p6bb_g"/><path class="d6pp-1ias"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:commercial-property" /></template>
<style>
.d6pp-1ias {
  d: path("M8.5 12.5h7v8h-7Z");
}

.ua6p6bb_g {
  d: path("M4 8h16v12.5H4ZM3 8l2-4h14l2 4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
