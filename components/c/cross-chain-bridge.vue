<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="chawtrb7b"/><path class="k-rjd4buf"/><path class="cpyr62b6m"/><path class="jd93cabqu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cross-chain-bridge" /></template>
<style>
.chawtrb7b {
  d: path("m6 12l3.5 2v4L6 20l-3.5-2v-4Z");
}

.cpyr62b6m {
  d: path("m14.5 14l3.5 2l3.5-2M18 16v4M6 9c0-5.5 12-5.5 12 0");
}

.jd93cabqu {
  d: path("M16.25 7.25L18 9l1.75-1.75");
}

.k-rjd4buf {
  d: path("M2.5 14L6 16l3.5-2M6 16v4m12-8l3.5 2v4L18 20l-3.5-2v-4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
