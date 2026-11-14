<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qj7ya3bni"/><path class="fbv6vbbeb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:crepuscular-rays" /></template>
<style>
.fbv6vbbeb {
  d: path("M12 7.5a3.5 3.5 0 0 1 0 7m4.5 1l3 3m-12-3l-3 3m7.5-1.25v4.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qj7ya3bni {
  d: path("M6.5 11h11a2.5 2.5 0 0 0 0-5a4 4 0 0 0-7.5.5A3 3 0 0 0 6.5 11");
}

</style>
