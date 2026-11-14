<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t3u1u75zu"/><path class="t9t177f2i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:in-flight-entertainment" /></template>
<style>
.t3u1u75zu {
  d: path("M4 3.5h16v12H4Z");
}

.t9t177f2i {
  d: path("M10.5 7v5l4-2.5ZM7 18h10m-5-2.5V18");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
