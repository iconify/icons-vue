<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ni27ohb4d"/><path class="m19mowbhm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:golf-hole-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.m19mowbhm {
  d: path("M14.0938 15.0519L15 15.1373C19.0571 15.5196 22 16.6567 22 18C22 19.6569 17.5228 21 12 21C6.4772 21 2 19.6569 2 18C2 16.8895 4.011 15.92 7 15.4013L7.829 15.2574M11 3L20 6L11 9L11 3ZM11 3L11 17L11 18");
}

.ni27ohb4d {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11.3162 2.0513L20.3162 5.0513C20.7246 5.1874 21 5.5696 21 6C21 6.4304 20.7246 6.8126 20.3162 6.9487L11.3162 9.9487C11.2142 9.9827 11.1074 10 10.9999 10C10.4476 10 9.9999 9.5523 10 9L10 3C9.9999 2.4477 10.4476 2 10.9999 2C11.1074 2 11.2142 2.0173 11.3162 2.0513Z");
  stroke: none;
}

</style>
