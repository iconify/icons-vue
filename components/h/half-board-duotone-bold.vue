<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="tt-5y-ilt"/><path class="ycftzzhuq"/><path class="x5llwmzwn"/><path class="keeez031w"/><path class="l2nbo7bgf"/><path class="l8dn9jbyp"/><path class="tla8vyn6c"/><path class="olqfcgidt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:half-board-duotone-bold" /></template>
<style>
.keeez031w {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 19h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l2nbo7bgf {
  d: path("M4 15a8 8 0 0 1 16 0");
}

.l8dn9jbyp {
  d: path("M2 15h20");
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

.tla8vyn6c {
  d: path("M12 7v8");
}

.tt-5y-ilt {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 15a8 8 0 0 1 16 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x5llwmzwn {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 7v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ycftzzhuq {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 15h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
