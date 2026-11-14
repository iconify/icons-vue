<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d2n3fubcl"/><path class="t2d3u0b9h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cool-roof" /></template>
<style>
.d2n3fubcl {
  d: path("m3.5 13.5l8.5-6l8.5 6v8h-17Z");
}

.t2d3u0b9h {
  d: path("M10 21.5v-4h4v4M6.5 8L4.25 5M12 4.75V2.5M17.5 8l2.25-3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
