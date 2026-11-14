<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hneliqdkn"/><path class="bimnh7byq"/><path class="wj9_-kb4f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dj-cue" /></template>
<style>
.bimnh7byq {
  d: path("M5.5 12a5 5 0 1 0 10 0a5 5 0 1 0-10 0Z");
}

.hneliqdkn {
  d: path("M2.5 4h19v16h-19Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wj9_-kb4f {
  d: path("m10.5 7l1.75 2.75h-3.5Zm8 .5v9");
}

</style>
