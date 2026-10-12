<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="enu5zfr2f"/><path class="p4ouqgbun"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:arm-flex" /></template>
<style>
.enu5zfr2f {
  d: path("m4.02 12.2l2.21-1.4q1.27-.8 2.76-.63l1.52.16q1.49.17 2.62-.58q1.12-.75 1.25-2Q14.5 6.5 14 5.5t.25-1.87q.75-.88 2.25-.88h1.25q1.5 0 2.13.88q.62.87 0 2q-.63 1.12-.36 2.6l.96 5.29q.27 1.48-.13 2.93l-.45 1.6q-.4 1.45-1.74 2.12l-.32.16Q16.5 21 15 21H4.25q-1.5 0-1.5-1.5v-5q0-1.5 1.27-2.3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p4ouqgbun {
  d: path("M5.5 16c1.5-1.75 3.5-2.75 5-2.75S13.5 14 15 16q-2.25 2.25-4.5 2.25c-2.25 0-3.5-.75-5-2.25");
}

</style>
