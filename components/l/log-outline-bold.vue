<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="abnm6smsv"/><path class="d2gpzsh-s"/><path class="qpr4gub3m"/><path class="v_xc_lbja"/><path class="xou73ccee"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:log-outline-bold" /></template>
<style>
.abnm6smsv {
  d: path("M13 3H6v18h12V8");
}

.d2gpzsh-s {
  d: path("M9 6v12");
}

.qpr4gub3m {
  d: path("M11 9h5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.v_xc_lbja {
  d: path("M11 13h5");
}

.xou73ccee {
  d: path("M11 17h3");
}

</style>
