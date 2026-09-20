<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="a6r83470a"/><path class="vzsghy7ub"/><path class="lyqw31v8s"/><path class="did41pbsp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:anatomy-heart-outline-bold" /></template>
<style>
.a6r83470a {
  d: path("M9 20c-3 -3 -4 -7 -3 -10s4 -4 6 -2c2 -2 5 -1 6 2s0 7 -3 10Z");
}

.did41pbsp {
  d: path("m15 7 3 -3");
}

.lyqw31v8s {
  d: path("M11 7V3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vzsghy7ub {
  d: path("M9 7 6 4");
}

</style>
