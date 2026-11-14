<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x564sptlv"/><path class="fuk-54b1c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:auto-tag" /></template>
<style>
.fuk-54b1c {
  d: path("M13 10c.1 2 .9 2.9 3 3c-2.1.1-2.9 1-3 3c-.1-2-.9-2.9-3-3c2.1-.1 2.9-1 3-3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x564sptlv {
  d: path("M3.5 3.5H12l8.5 8.5l-8.5 8.5L3.5 12ZM8 8h.01");
}

</style>
