<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fj343abxx"/><path class="atv66_b1j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:camellia" /></template>
<style>
.atv66_b1j {
  d: path("M10 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.fj343abxx {
  d: path("M12 4.5a4.75 4.75 0 0 1 7.25 5.25A4.75 4.75 0 0 1 16.5 18a4.75 4.75 0 0 1-9 0a4.75 4.75 0 0 1-2.75-8.25A4.75 4.75 0 0 1 12 4.5Zm0 0v2.75m7.25 2.5l-2.75.75m0 7.5l-1.75-2.25M7.5 18l1.75-2.25m-4.5-6l2.75.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
