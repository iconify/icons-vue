<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jt4-jw3vg"/><path class="zaqowkart"/><path class="skbifdbcx"/><path class="a-m7xvbdg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:heartbeat-agent-duotone-bold" /></template>
<style>
.a-m7xvbdg {
  d: path("M10 18h3l2.5 -2.5L18 18h3");
}

.jt4-jw3vg {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8.69 3.37a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.skbifdbcx {
  d: path("M8.69 3.37a4 4 0 1 1 -3.38 0");
}

.zaqowkart {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 18h3l2.5 -2.5L18 18h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
