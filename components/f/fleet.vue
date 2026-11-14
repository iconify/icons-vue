<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mve7j4bks"/><path class="zm9qeexje"/><path class="ll9ltzefv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fleet" /></template>
<style>
.ll9ltzefv {
  d: path("M7.5 19a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm7.5 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.mve7j4bks {
  d: path("M3.5 16V4.5A1.5 1.5 0 0 1 5 3h7.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zm9qeexje {
  d: path("M6.5 17V7.5a1 1 0 0 1 1-1h7V10h3l3 3v4Z");
}

</style>
