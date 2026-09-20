<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="t5k5h0b_y"/><path class="xrewtmnla"/><path class="uaizx0bey"/><path class="d_ske9b8y"/><path class="zkgvk4bog"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:bird-cage-duotone-bold" /></template>
<style>
.d_ske9b8y {
  d: path("M15 7v13");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t5k5h0b_y {
  fill: currentColor;
  d: path("M5 20v-8c0 -4 3 -7 7 -7s7 3 7 7v8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.uaizx0bey {
  d: path("M9 7v13");
}

.xrewtmnla {
  d: path("M5 20v-8c0 -4 3 -7 7 -7s7 3 7 7v8Z");
}

.zkgvk4bog {
  d: path("M12 2v3");
}

</style>
