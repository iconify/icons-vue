<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iw4_dj7he"/><path class="ffxbyiwvk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:car-heater-seat" /></template>
<style>
.ffxbyiwvk {
  d: path("M12 11.5c-1-1.25 1-2.5 0-3.75s1-2.5 0-3.75m4.5 7.5c-1-1.25 1-2.5 0-3.75s1-2.5 0-3.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iw4_dj7he {
  d: path("M4.5 3.5h.75Q7 3.5 7.27 5.23l1.21 7.54q.27 1.73 2.02 1.73h7.75q1.75 0 1.97 1.74l.06.52q.22 1.74-1.53 1.74H6.25q-1.75 0-1.95-1.74L2.95 5.24Q2.75 3.5 4.5 3.5m4.5 15v2.75m7-2.75v2.75");
}

</style>
