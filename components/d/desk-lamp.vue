<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h941fbllu"/><path class="vj2kgkiaz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:desk-lamp" /></template>
<style>
.h941fbllu {
  d: path("m13.79 5.21l-.58.58q-.71.71-.31 1.63l1.95 4.41q.4.92 1.11.21l4.08-4.08q.71-.71-.21-1.11L15.42 4.9q-.92-.4-1.63.31");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vj2kgkiaz {
  d: path("M8.75 21L5.5 13.75l8-8.25M4.25 21h9");
}

</style>
