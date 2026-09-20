<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="srzgk7jml"/><path class="ic_pehd5a"/><path class="fbw2ldgtv"/><path class="xsyfe-byx"/><path class="mvo4nxq3c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:car-dashboard-outline-bold" /></template>
<style>
.fbw2ldgtv {
  d: path("M12 10v7");
}

.ic_pehd5a {
  d: path("M3 17h18");
}

.mvo4nxq3c {
  d: path("M16 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.srzgk7jml {
  d: path("M3 17a9 9 0 0 1 18 0");
}

.xsyfe-byx {
  d: path("M6 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
