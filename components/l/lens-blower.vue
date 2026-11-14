<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vy3vtac-a"/><path class="rzsmeacgn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lens-blower" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rzsmeacgn {
  d: path("m11 11l5-4.25L17.25 8L13 13m5-9l1.75-1.75M20 6l1.75-1.75");
}

.vy3vtac-a {
  d: path("M3 15.5a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0");
}

</style>
