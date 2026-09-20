<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="vn29_9bge"/><path class="m4kvcyf5g"/><path class="itcs4-8rc"/><path class="keeez031w"/><path class="t4l7c7bim"/><path class="xctejrqwn"/><path class="nqnw98byf"/><path class="olqfcgidt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:hill-duotone-bold" /></template>
<style>
.itcs4-8rc {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 14h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.keeez031w {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 19h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.m4kvcyf5g {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 14a5 5 0 0 1 10 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nqnw98byf {
  d: path("M2 14h20");
}

.olqfcgidt {
  d: path("M6 19h12");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t4l7c7bim {
  d: path("M2 14a7 7 0 0 1 14 0");
}

.vn29_9bge {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 14a7 7 0 0 1 14 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xctejrqwn {
  d: path("M12 14a5 5 0 0 1 10 0");
}

</style>
