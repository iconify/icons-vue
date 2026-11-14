<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="y5qk62bqx"/><path class="h3x4zxbvq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fundraising-page" /></template>
<style>
.h3x4zxbvq {
  d: path("m18 21.25l-2.75-2.75A2 2 0 0 1 18 15.75a2 2 0 0 1 2.75 2.75Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y5qk62bqx {
  d: path("M13.3 20.5H2.5v-18h19v10.8M2.5 8h19M5.75 5.25h.01m2.99 0h.01M6 12.5h8");
}

</style>
