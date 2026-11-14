<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gfdz4thtj"/><path class="no73d75sv"/><path class="dcw16-bky"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hot-reload" /></template>
<style>
.dcw16-bky {
  fill: currentColor;
  d: path("m13 7.5l-4 5h3l-1 4l4-5h-3Z");
}

.gfdz4thtj {
  d: path("M16 5.072a8 8 0 0 1 0 13.856m-8 0A8 8 0 0 1 8 5.072");
}

.no73d75sv {
  d: path("M18.75 19.75L16 19l.75-3M5.25 4.25L8 5l-.75 3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
