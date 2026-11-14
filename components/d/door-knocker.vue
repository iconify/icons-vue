<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t4bkivbzy"/><path class="fi5a7guyo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:door-knocker" /></template>
<style>
.fi5a7guyo {
  d: path("M8 11.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0Z");
}

.t4bkivbzy {
  d: path("M5 2.5h14v19H5Zm7 3v2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
