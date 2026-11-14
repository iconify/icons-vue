<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rqiqv_bly"/><path class="c66pny1bi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dress-code" /></template>
<style>
.c66pny1bi {
  d: path("m8 3l4 4l4-4m-4 4za1.133 1.133 0 0 1 1.124.992l.797 6.38a1.5 1.5 0 0 1-.317 1.123L13 16.25a1.28 1.28 0 0 1-2 0l-.604-.755a1.5 1.5 0 0 1-.317-1.123l.797-6.38A1.133 1.133 0 0 1 12 7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rqiqv_bly {
  d: path("M8 3L3.5 5.5l-1 5.5L6 12v9h12v-9l3.5-1l-1-5.5L16 3");
}

</style>
