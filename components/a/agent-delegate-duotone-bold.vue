<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ydkocbbew"/><path class="u9_eh8ium"/><path class="vncstmb3g"/><path class="gnioxz0xf"/><path class="h7k_twb0c"/><path class="crfmflbxb"/><path class="ih1xqsb_s"/><path class="xb0ugqbkt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:agent-delegate-duotone-bold" /></template>
<style>
.crfmflbxb {
  d: path("m10 10 2.5 2.5");
}

.gnioxz0xf {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M19.27 15.28a3 3 0 1 1 -2.54 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h7k_twb0c {
  d: path("M7.27 3.28a3 3 0 1 1 -2.54 0");
}

.ih1xqsb_s {
  d: path("M11.5 14H14v-2.5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.u9_eh8ium {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m10 10 2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vncstmb3g {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M11.5 14H14v-2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xb0ugqbkt {
  d: path("M19.27 15.28a3 3 0 1 1 -2.54 0");
}

.ydkocbbew {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7.27 3.28a3 3 0 1 1 -2.54 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
