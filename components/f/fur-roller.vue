<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mprsatbia"/><path class="f_-_xvbte"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fur-roller" /></template>
<style>
.f_-_xvbte {
  d: path("M7 9.75c0-2 1.5-2.5 1.5-4.5m2 4.5c0-2 1.5-2.5 1.5-4.5");
}

.mprsatbia {
  d: path("M4 2.5h16a1 1 0 0 1 1 1v8a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1v-8a1 1 0 0 1 1-1Zm8 10v2.25m-1.75 0h3.5v6.75h-3.5ZM16.5 2.5v10");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
