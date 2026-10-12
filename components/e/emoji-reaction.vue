<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="ilxbjdbkq"/><circle class="gqdwd_bjh"/><path class="bd11gtbhg"/><path class="da_zfpbbn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:emoji-reaction" /></template>
<style>
.bd11gtbhg {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.25 15.25h.01m1.99 0h.01");
}

.da_zfpbbn {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16 17.75a1.8 1.8 0 0 0 2.5 0");
}

.gqdwd_bjh {
  cx: 17.25px;
  cy: 17.25px;
  r: 4px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ilxbjdbkq {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 3.25h8.5a2.5 2.5 0 0 1 2.5 2.5v6a2.5 2.5 0 0 1-2.5 2.5h-4.5L5.65 17c-.5.4-1.15.05-1.15-.55v-2.2a2.5 2.5 0 0 1-1.75-2.5v-6a2.5 2.5 0 0 1 2.5-2.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
