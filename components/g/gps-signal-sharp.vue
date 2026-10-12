<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="tmo_7g80s"/><path class="qhkm0qbjx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gps-signal-sharp" /></template>
<style>
.qhkm0qbjx {
  d: path("M10.75 12.25a1.75 1.75 0 1 1-3.5 0a1.75 1.75 0 1 1 3.5 0M15 2.75A6.25 6.25 0 0 1 21.25 9M15 6.25h2.75V9");
}

.tmo_7g80s {
  d: path("M9 21.25h-.474l-.346-.33C5.7 18.6 3.25 15.6 3.25 12.25a5.75 5.75 0 0 1 11.5 0c0 3.35-2.45 6.35-4.93 8.67l-.346.33z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
