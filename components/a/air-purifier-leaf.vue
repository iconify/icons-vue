<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e8gp827lm"/><path class="q3otxzrlc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:air-purifier-leaf" /></template>
<style>
.e8gp827lm {
  d: path("M5.5 2.5h13v19h-13ZM9 6h6");
}

.q3otxzrlc {
  d: path("M9 18c0-5 2-8 6.5-8.5c0 5-2.5 8-6.5 8.5Zm0 0l3.5-4.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
