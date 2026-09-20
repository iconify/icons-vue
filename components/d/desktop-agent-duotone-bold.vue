<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="rpia7ss3x"/><path class="ttk4e4b0g"/><path class="jc8gzdbty"/><path class="fmlaifbpn"/><path class="qw7b_6b1t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:desktop-agent-duotone-bold" /></template>
<style>
.fmlaifbpn {
  d: path("M12 16v4");
}

.jc8gzdbty {
  d: path("M13.5 6.33a3.5 3.5 0 1 1 -2.96 0");
}

.qw7b_6b1t {
  d: path("M8 20h8");
}

.rpia7ss3x {
  fill: currentColor;
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v9a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.ttk4e4b0g {
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v9a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

</style>
