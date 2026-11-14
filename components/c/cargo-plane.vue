<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cff5f3u1q"/><path class="uuf4k9lzd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cargo-plane" /></template>
<style>
.cff5f3u1q {
  d: path("M13.162 19.468L10.5 18.5l-2.75 1v-2L9 16v-5l-6.5 1.5V11L9 8.5v-3c0-1.5.25-3 1.5-3S12 4 12 5.5v3l6.5 2.5v1.5L12 11v5l.926 1.111M19 15.75l3 1.5v3.25L19 22l-3-1.5v-3.25Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uuf4k9lzd {
  d: path("m16 17.25l3 1.5l3-1.5m-3 1.5V22");
}

</style>
