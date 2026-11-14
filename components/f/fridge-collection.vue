<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kw4m-t0du"/><path class="v-1g9bc9b"/><path class="pp4k7rgkr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fridge-collection" /></template>
<style>
.kw4m-t0du {
  d: path("M3 3h8.5v14.5H3Z");
}

.pp4k7rgkr {
  d: path("M4.5 19.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm11 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM3 7.5h8.5m-3 3V14");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v-1g9bc9b {
  d: path("M2.5 17.5h19v-4L18 10h-3.5v7.5");
}

</style>
