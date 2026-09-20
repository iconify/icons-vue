<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="inzw2gkjz"/><path class="hpny8kbnk"/><path class="n2zqrbdgd"/><path class="ooyv_6epc"/><path class="jfhg8zbol"/><path class="jlojnsdlu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:free-wifi-duotone-bold" /></template>
<style>
.hpny8kbnk {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7.77 15.46a4.5 4.5 0 0 1 8.46 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.inzw2gkjz {
  fill: currentColor;
  d: path("M11 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.jfhg8zbol {
  d: path("M3.54 13.92a9 9 0 0 1 16.92 0");
}

.jlojnsdlu {
  d: path("M11 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.n2zqrbdgd {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3.54 13.92a9 9 0 0 1 16.92 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ooyv_6epc {
  d: path("M7.77 15.46a4.5 4.5 0 0 1 8.46 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
