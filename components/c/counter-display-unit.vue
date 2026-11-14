<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sfk_huiqm"/><path class="kph67ubbs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:counter-display-unit" /></template>
<style>
.kph67ubbs {
  d: path("M7 16.5V10h3v6.5m4 0V10h3v6.5");
}

.sfk_huiqm {
  d: path("M4.5 13.5V4A1.5 1.5 0 0 1 6 2.5h12A1.5 1.5 0 0 1 19.5 4v9.5m-17 0l4 3h11l4-3v8h-19ZM8 5.75h8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
