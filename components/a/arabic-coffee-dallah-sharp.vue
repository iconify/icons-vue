<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="u7rj1xb2j"/><path class="py26cm5pi"/><path class="yywvzbbul"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:arabic-coffee-dallah-sharp" /></template>
<style>
.py26cm5pi {
  d: path("M8.5 11.75C6 11.25 4.5 9 4 6.5l-.266-1.328L5 4.75M15 9.5c3.5 0 4.75 3.75 2 7.25");
}

.u7rj1xb2j {
  d: path("M12 2.75v3M9.25 8.5a2.75 2.75 0 0 1 5.5 0Zm.75 0h4.75l.17.73l.91 3.79l.17.73H8l.17-.73l.91-3.79l.17-.73z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yywvzbbul {
  d: path("M8 13.75h8L17.75 19l.66 2.214l-2.31.036H7.9l-2.31-.036L6.25 19ZM7.25 17h9.5");
}

</style>
