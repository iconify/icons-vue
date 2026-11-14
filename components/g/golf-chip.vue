<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qk1idkihy"/><path class="s_bco4bom"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:golf-chip" /></template>
<style>
.qk1idkihy {
  d: path("M2.5 18c3.5-5 15.5-5 19 0");
}

.s_bco4bom {
  d: path("M8 10.25a4 4 0 1 0 8 0a4 4 0 1 0-8 0ZM6 16l-1-3.75M18 16l1-3.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
