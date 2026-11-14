<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fk4ngo-8r"/><path class="a2f417rye"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:camping-lantern" /></template>
<style>
.a2f417rye {
  d: path("M12 11.5c1.25 1.25 1.75 2 1.75 3a1.75 1.75 0 0 1-3.5 0c0-1 .5-1.75 1.75-3Z");
}

.fk4ngo-8r {
  d: path("M9.5 6V4.5a2.5 2.5 0 0 1 5 0V6M6 8.5L8.5 6h7L18 8.5Zm1 0h10V19H7ZM6 19h12v2.5H6Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
