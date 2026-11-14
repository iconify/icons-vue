<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="svgk6v05l"/><path class="f4-iowb5h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:landing-page-hero" /></template>
<style>
.f4-iowb5h {
  d: path("M6 10.5h12V14H6Zm0 6.25h4.5m3 0H18");
}

.svgk6v05l {
  d: path("M2.5 4h19v16h-19Zm0 3.75h19");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
