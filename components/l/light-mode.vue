<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="ewlowibrc"/><path class="kuir43afd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:light-mode" /></template>
<style>
.ewlowibrc {
  cx: 12px;
  cy: 12px;
  r: 4.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kuir43afd {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3.75h.01m5.82 2.42h.01M20.25 12h.01m-2.43 5.83h.01M12 20.25h.01m-5.84-2.42h.01M3.75 12h.01m2.41-5.83h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
