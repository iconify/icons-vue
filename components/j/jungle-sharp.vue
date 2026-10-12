<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="c9ro_pbgr"/><path class="yy7qbkbdl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:jungle-sharp" /></template>
<style>
.c9ro_pbgr {
  d: path("M12.25 16.5c-2.4.75-6-1.1-4.1-6.3c1.55-4.2 5.4-6 8.55-5.9a8.92 8.92 0 0 1 2.75 10c-1.9 5.2-5.85 4.3-7.2 2.2Zm-5.1-5.05l4.15-.35M9.2 7.3L13 8m7.25 5.55l-3-2.7");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yy7qbkbdl {
  d: path("M12.25 16.5c0 3-1.75 4.75-4.5 4.75H3.5V5.5m0 0V3h4v3H6.25");
}

</style>
