<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h7k_twb0c"/><path class="jt9_y_e3f"/><path class="d_0vbfv0w"/><path class="ad0-p6dru"/><path class="wylvx_bde"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:agent-swarm-outline-thin" /></template>
<style>
.ad0-p6dru {
  d: path("M12.27 10.28a3 3 0 1 1 -2.54 0");
}

.d_0vbfv0w {
  d: path("M20.27 11.28a3 3 0 1 1 -2.54 0");
}

.h7k_twb0c {
  d: path("M7.27 3.28a3 3 0 1 1 -2.54 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jt9_y_e3f {
  d: path("M17.27 2.28a3 3 0 1 1 -2.54 0");
}

.wylvx_bde {
  d: path("M8.27 16.28a3 3 0 1 1 -2.54 0");
}

</style>
