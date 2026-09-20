<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l4i2yo_dl"/><path class="tuabbzxqz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:csrf-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l4i2yo_dl {
  d: path("M15 4h5v8l-8 8 -8 -8V4h5Z");
}

.tuabbzxqz {
  d: path("m9 11 3 3 5 -5");
}

</style>
