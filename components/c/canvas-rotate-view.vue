<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lkz2-8bjm"/><path class="zm8zyabwd"/><path class="gmk6y83je"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:canvas-rotate-view" /></template>
<style>
.gmk6y83je {
  d: path("m3 4.5l3 .25l-.25 3");
}

.lkz2-8bjm {
  d: path("M8 8h8v8H8Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zm8zyabwd {
  d: path("M15.249 3.073a9.5 9.5 0 1 1-9.355 1.65");
}

</style>
