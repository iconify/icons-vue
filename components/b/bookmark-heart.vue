<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="m_os4qq9l"/><path class="gpw5emb7p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bookmark-heart" /></template>
<style>
.gpw5emb7p {
  d: path("M12 12s-3-2-3-3.75c0-1 .75-1.75 1.5-1.75s1.25.5 1.5 1c.25-.5.75-1 1.5-1s1.5.75 1.5 1.75C15 10 12 12 12 12Z");
}

.m_os4qq9l {
  d: path("M6 3h12v18l-6-4.5L6 21Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
