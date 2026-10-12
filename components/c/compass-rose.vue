<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="efsba9b2h"/><path class="to8m3ibcr"/><path class="jqe8f_bjb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:compass-rose" /></template>
<style>
.efsba9b2h {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75q1.11 8.14 9.25 9.25q-8.14 1.11-9.25 9.25q-1.11-8.14-9.25-9.25q8.14-1.11 9.25-9.25");
}

.jqe8f_bjb {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.5 6.5l1.75 1.75M17.5 6.5l-1.75 1.75M6.5 17.5l1.75-1.75m9.25 1.75l-1.75-1.75");
}

.to8m3ibcr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
