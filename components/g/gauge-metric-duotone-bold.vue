<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dh-nlhghu"/><path class="jiw8u-asa"/><path class="qj7jubcuz"/><path class="u5g9scbnx"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="e2evtpg8i"/><path class="s1pdfd1ij"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:gauge-metric-duotone-bold" /></template>
<style>
.dh-nlhghu {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.e2evtpg8i {
  d: path("M9.5 9.5 12 7l2.5 2.5");
}

.jiw8u-asa {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.qj7jubcuz {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9.5 9.5 12 7l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r3faxubne {
  d: path("M4 4v16");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.s1pdfd1ij {
  d: path("M9.5 14.5 12 17l2.5 -2.5");
}

.u5g9scbnx {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9.5 14.5 12 17l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
