<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="oduefbkld"/><path class="ioz5nd6-g"/><path class="m_in0_0sg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fleet-map" /></template>
<style>
.ioz5nd6-g {
  d: path("M9.5 11.5h7v7h-7Zm7 2.5H19l2.5 2.5v2h-5");
}

.m_in0_0sg {
  d: path("M11 20a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm6.25 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.oduefbkld {
  d: path("M16 8.75V3l-4.75 1.5L6.75 3L2.5 4.5V15l4.25-1.5V3m4.5 1.5v4.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
