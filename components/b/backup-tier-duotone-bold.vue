<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="vpv504bbj"/><path class="st4jvibbh"/><path class="v-v1vx84b"/><path class="xpjur0b_h"/><path class="amujw3_wp"/><path class="lf67ljb6v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:backup-tier-duotone-bold" /></template>
<style>
.amujw3_wp {
  d: path("m9.5 13 2.5 2.5 2.5 -2.5");
}

.lf67ljb6v {
  d: path("M4 19.25A2.25 2.25 0 0 1 6.25 17h11.5A2.25 2.25 0 0 1 20 19.25a2.25 2.25 0 0 1 -2.25 2.25H6.25A2.25 2.25 0 0 1 4 19.25");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.st4jvibbh {
  fill: currentColor;
  d: path("M4 19.25A2.25 2.25 0 0 1 6.25 17h11.5A2.25 2.25 0 0 1 20 19.25a2.25 2.25 0 0 1 -2.25 2.25H6.25A2.25 2.25 0 0 1 4 19.25");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.v-v1vx84b {
  d: path("M4 5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

.vpv504bbj {
  fill: currentColor;
  d: path("M4 5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.xpjur0b_h {
  d: path("M12 11.5V14");
}

</style>
