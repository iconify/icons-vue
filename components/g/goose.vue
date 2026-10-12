<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="zhv94zb-w"/><path class="s3arf0jez"/><path class="a2mhuibjy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:goose" /></template>
<style>
.a2mhuibjy {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 5.5h.01");
}

.s3arf0jez {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.4 5L2.75 6.1L5.5 7Zm6.6 9c1.75 1.25 4 1.75 6.5 1.5m-7.5 4v1.75m3-1.75v1.75");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zhv94zb-w {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 5.75C5.25 4.25 6.5 3 8 3s2.75 1.25 2.75 2.75v4.75L18 11.75c1.75.3 3 1.75 3 3.5c0 2.5-2.25 4.25-5 4.25h-4.25c-3 0-4.75-2.25-4.75-5c0-1.25.5-2.5 1.25-3.5V8.5H8c-1.5 0-2.75-1.25-2.75-2.75");
}

</style>
