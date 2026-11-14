<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i2b37k5qn"/><path class="n---c0b3n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:back-protector" /></template>
<style>
.i2b37k5qn {
  d: path("M7 2.5h10c2 0 3.5 1.5 3.5 3.5v3.5c0 2-2.5 3.5-3.5 5.5v4.5c0 1.25-1 2-2.25 2h-5.5C8 21.5 7 20.75 7 19.5V15c-1-2-3.5-3.5-3.5-5.5V6C3.5 4 5 2.5 7 2.5Z");
}

.n---c0b3n {
  d: path("M10.25 2.5h3.5v19h-3.5Zm0 6.25h3.5M10.25 15h3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
