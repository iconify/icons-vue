<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="xjfmr4bmi"/><path class="yr9hq3hlt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:audible-signal-sharp" /></template>
<style>
.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xjfmr4bmi {
  d: path("M4.75 2.75h9v13h-9z");
}

.yr9hq3hlt {
  d: path("M9.25 12V6.5m-2 2l2-2l2 2m-2 7.25v5.5M16.5 6.5l2.604 2.75L16.5 12M19 4.5a7 7 0 0 1 0 9.5");
}

</style>
