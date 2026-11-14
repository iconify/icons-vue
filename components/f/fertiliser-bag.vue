<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="adgv6acea"/><path class="o5kzzybqi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fertiliser-bag" /></template>
<style>
.adgv6acea {
  d: path("M9 7.5C5 10 3.5 15 4.5 19.5q.5 2 2.5 2h10q2 0 2.5-2c1-4.5-.5-9.5-4.5-12m-6 0L7 3h10l-2 4.5m-7 0h8");
}

.o5kzzybqi {
  d: path("M7.5 12h9v4.5h-9Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
