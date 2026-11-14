<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qwkzdyb0f"/><path class="p7uvmrbua"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lab" /></template>
<style>
.p7uvmrbua {
  d: path("M16 7V4h2v4.75M11 8v2.25l-2.5 3.5h7l-2.5-3.5V8m-2.75 12.5v-2a1.75 1.75 0 0 1 3.5 0v2");
}

.qwkzdyb0f {
  d: path("m4 10.5l8-7l8 7v10H4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
