<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="txqgcyphc"/><path class="t4wfbu4kp"/><path class="uorymuo0h"/><path class="ky4omnbla"/><path class="e5k2eotmk"/><path class="ei5j_bckv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:credit-report-duotone-bold" /></template>
<style>
.e5k2eotmk {
  d: path("M9 11a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.ei5j_bckv {
  d: path("M11.5 11.5 15 15");
}

.ky4omnbla {
  d: path("M4 5h14l4 4v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2V7a2 2 0 0 1 2 -2m14 0v4h4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t4wfbu4kp {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 5h14l4 4v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2V7a2 2 0 0 1 2 -2m14 0v4h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.txqgcyphc {
  fill: currentColor;
  d: path("M9 11a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.uorymuo0h {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M11.5 11.5 15 15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
