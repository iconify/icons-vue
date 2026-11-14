<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j17w3_oex"/><path class="sl-9hjbka"/><path class="m08jlab5f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:database-table" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j17w3_oex {
  d: path("M12.594 21.242q-.294.008-.594.008c-4.4 0-8-1.25-8-2.75v-13C4 4 7.6 2.75 12 2.75S20 4 20 5.5v6.755");
}

.m08jlab5f {
  d: path("M4 5.5C4 7 7.6 8.25 12 8.25S20 7 20 5.5M4 12c0 1.2 2.3 2.2 5.5 2.5m7.25.5h2.5A1.75 1.75 0 0 1 21 16.75v2.5A1.75 1.75 0 0 1 19.25 21h-2.5A1.75 1.75 0 0 1 15 19.25v-2.5A1.75 1.75 0 0 1 16.75 15M15 18h6m-3-3v6");
}

.sl-9hjbka {
  d: path("M4 5.5C4 7 7.6 8.25 12 8.25S20 7 20 5.5M4 12c0 1.5 3.6 2.75 8 2.75q.305 0 .604-.008");
}

</style>
