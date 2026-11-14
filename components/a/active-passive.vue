<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xmh1vmjaj"/><path class="sev4z9b1w"/><path class="me0yc5b4p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:active-passive" /></template>
<style>
.me0yc5b4p {
  d: path("M5.75 17.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.sev4z9b1w {
  fill: currentColor;
  d: path("M5.75 6.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xmh1vmjaj {
  d: path("M3 2.5h18v8H3Zm0 10.75h18v8H3Z");
}

</style>
