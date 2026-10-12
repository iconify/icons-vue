<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ko7r1ac8q"/><path class="x5_sz_xir"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cubesat" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ko7r1ac8q {
  d: path("m12.89 6.2l4.72 2.35q.89.45.89 1.45v6q0 1-.89 1.45l-4.72 2.35q-.89.45-1.78 0l-4.72-2.35Q5.5 17 5.5 16v-6q0-1 .89-1.45l4.72-2.35q.89-.45 1.78 0");
}

.x5_sz_xir {
  d: path("m5.5 9l6.5 3.25L18.5 9M12 12.25v8m-3.25-9.62v8M5.5 13l6.5 3.25m3.25-8.87l4.25-4.63");
}

</style>
