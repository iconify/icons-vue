<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="a8sksubhe"/><path class="ahhqo1b4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bookmark-off-sharp-fill" /></template>
<style>
.a8sksubhe {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M21 21L21 22C21 22.5523 20.5523 23 20 23C19.8593 23 19.7202 22.9703 19.5918 22.9129L12 19.5177L4.4082 22.9129C4.2798 22.9703 4.1407 23 4 23C3.4477 23 3 22.5523 3 22L3 3L21 21ZM4.6569 1L20 1C20.5523 1 21 1.4477 21 2L21 17.3431L4.6569 1Z");
  stroke: none;
}

.ahhqo1b4s {
  d: path("M1.7071 1.7071L22.2929 22.2929");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
