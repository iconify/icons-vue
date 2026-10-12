<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d02scy2nh"/><rect class="xb8_egb3s"/><path class="y942ybcdk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:audio-jack" /></template>
<style>
.d02scy2nh {
  d: path("M10.5 9.75v-5.5a1.5 1.5 0 0 1 3 0v5.5Zm0-3h3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xb8_egb3s {
  width: 6.5px;
  height: 7.5px;
  x: 8.75px;
  y: 9.75px;
  rx: 1.5px;
}

.y942ybcdk {
  d: path("M12 17.25v4");
}

</style>
