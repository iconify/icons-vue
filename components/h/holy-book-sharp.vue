<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="vn6ehqbcs"/><path class="sqwko47gs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:holy-book-sharp" /></template>
<style>
.sqwko47gs {
  d: path("M13.5 6.75q.45 3.3 3.75 3.75q-3.3.45-3.75 3.75q-.45-3.3-3.75-3.75q3.3-.45 3.75-3.75Z");
}

.vn6ehqbcs {
  d: path("M4.75 2.75h14.5v18.5H4.75zm3 0v18.5m0-3h11.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
