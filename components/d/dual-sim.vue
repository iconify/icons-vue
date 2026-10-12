<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a15emwd4f"/><path class="wy35dh1ie"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dual-sim" /></template>
<style>
.a15emwd4f {
  d: path("M11.75 8.75h4.5q1.5 0 2.56 1.06l1.38 1.38q1.06 1.06 1.06 2.56v6q0 1.5-1.5 1.5h-8q-1.5 0-1.5-1.5v-9.5q0-1.5 1.5-1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wy35dh1ie {
  d: path("M13.75 8.75v-2.5l-3.5-3.5h-5a2.5 2.5 0 0 0-2.5 2.5v7.5a2.5 2.5 0 0 0 2.5 2.5h5m3.75-1h3.5v4H14Z");
}

</style>
