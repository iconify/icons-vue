<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="tt6zglb3c"/><path class="yaciumivm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fire-watch-sharp" /></template>
<style>
.tt6zglb3c {
  d: path("M12 21.25a6.75 6.75 0 0 0 6.75-6.75c0-4.25-3-6.5-4.5-11.75c-1 2.75-2.25 4-3.75 5.25l-.75-1.5l-1-1c-2.25 2.5-3.5 5-3.5 9A6.75 6.75 0 0 0 12 21.25Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yaciumivm {
  d: path("M12 18.75h2.5v-2.5c0-1.5-1-2.5-2.5-4.25c-1.5 1.75-2.5 2.75-2.5 4.25v2.5z");
}

</style>
