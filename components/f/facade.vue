<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n-dsno60t"/><path class="qbyvhnb7o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:facade" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n-dsno60t {
  d: path("M2.75 20.75V9.5q0-.5.35-.86l1.95-2.03q.35-.36.69 0l1.92 2.03Q8 9 8 8.5V6q0-.5.5-.5H9q.5 0 .5-.5v-.5q0-.5.5-.5h.25q.5 0 .5-.5v-.25q0-.5.5-.5h1.5q.5 0 .5.5v.25q0 .5.5.5H14q.5 0 .5.5V5q0 .5.5.5h.5q.5 0 .5.5v2.5q0 .5.34.14l1.92-2.03q.34-.36.69 0l1.95 2.03q.35.36.35.86v11.25q0 .5-.5.5H3.25q-.5 0-.5-.5M5.4 12v2m0 2.5v2M18.6 12v2m0 2.5v2M12 7.75v1.5m-1.5 3.25h3");
}

.qbyvhnb7o {
  d: path("M10.75 21.25v-3.5a1.25 1.25 0 0 1 2.5 0v3.5");
}

</style>
