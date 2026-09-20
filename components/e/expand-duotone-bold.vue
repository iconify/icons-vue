<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="tqyubsikb"/><path class="adichbbyb"/><path class="dfpiqobnk"/><path class="jkq_i9bfa"/><path class="cpjt28hee"/><path class="qbycr98pd"/><path class="vw4ruuxbu"/><path class="o32gc9b6a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:expand-duotone-bold" /></template>
<style>
.adichbbyb {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m4 4 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.cpjt28hee {
  d: path("M4 10V4h6");
}

.dfpiqobnk {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 20h6v-6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jkq_i9bfa {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m20 20 -6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.o32gc9b6a {
  d: path("m20 20 -6 -6");
}

.qbycr98pd {
  d: path("m4 4 6 6");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tqyubsikb {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 10V4h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vw4ruuxbu {
  d: path("M14 20h6v-6");
}

</style>
