<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="bbnc0bnzm"/><path class="c9-bs0bxg"/><path class="acr9bfbxo"/><path class="fce-vbb2c"/><path class="z6s_w0bbl"/><path class="a7h45wbtv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:deploy-agent-duotone-bold" /></template>
<style>
.a7h45wbtv {
  d: path("M15.5 8.5 18 6l2.5 2.5");
}

.acr9bfbxo {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15.5 8.5 18 6l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.bbnc0bnzm {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10.11 9.47a5 5 0 1 1 -4.22 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.c9-bs0bxg {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18 8v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fce-vbb2c {
  d: path("M10.11 9.47a5 5 0 1 1 -4.22 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.z6s_w0bbl {
  d: path("M18 8v11");
}

</style>
