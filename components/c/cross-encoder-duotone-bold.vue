<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="r3h7eeb8m"/><path class="kl2i1mylv"/><path class="hhx45xbgc"/><path class="sbvb_2b7d"/><path class="dwze-roqx"/><path class="gig9ivbwc"/><path class="kfs1394gk"/><path class="z5135gcut"/><path class="ba_a_obvy"/><path class="rzfubwb2e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cross-encoder-duotone-bold" /></template>
<style>
.ba_a_obvy {
  d: path("m8 16 4 -4");
}

.dwze-roqx {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 12h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gig9ivbwc {
  d: path("M2 8h6");
}

.hhx45xbgc {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m8 8 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kfs1394gk {
  d: path("M2 16h6");
}

.kl2i1mylv {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 16h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r3h7eeb8m {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 8h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rzfubwb2e {
  d: path("M12 12h10");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sbvb_2b7d {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m8 16 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.z5135gcut {
  d: path("m8 8 4 4");
}

</style>
