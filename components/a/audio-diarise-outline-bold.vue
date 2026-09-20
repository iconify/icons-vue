<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jq9hovbrs"/><path class="yomctlb4k"/><path class="q4p2jbb0u"/><path class="js960j4-t"/><path class="wm1sjab9x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:audio-diarise-outline-bold" /></template>
<style>
.jq9hovbrs {
  d: path("M14 4h5a3 3 0 0 1 3 3v7a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V7a3 3 0 0 1 3 -3h5");
}

.js960j4-t {
  d: path("M12 7.5v6");
}

.q4p2jbb0u {
  d: path("M5.5 10.5H9");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wm1sjab9x {
  d: path("M15 10.5h3.5");
}

.yomctlb4k {
  d: path("M7 17v4l4 -4");
}

</style>
