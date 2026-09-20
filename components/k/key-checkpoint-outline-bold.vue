<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="a0z9iab1m"/><path class="e2nq-yvbg"/><path class="xidycypec"/><path class="drjiz3bcf"/><path class="srznkzjjp"/><path class="xnsqncccr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:key-checkpoint-outline-bold" /></template>
<style>
.a0z9iab1m {
  d: path("M14 2h2.5a3 3 0 0 1 3 3v7a3 3 0 0 1 -3 3h-9a3 3 0 0 1 -3 -3V5a3 3 0 0 1 3 -3H10");
}

.drjiz3bcf {
  d: path("M12 21h2.5");
}

.e2nq-yvbg {
  d: path("M12 15v6");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.srznkzjjp {
  d: path("M9 5.5v6");
}

.xidycypec {
  d: path("M12 18h3");
}

.xnsqncccr {
  d: path("M9 6.5h5v4H9");
}

</style>
