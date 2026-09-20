<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="q1hzqkbyz"/><path class="jbr6u9bhr"/><path class="wn_zu_bwn"/><path class="qi0s8ibkf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:link-duotone-regular" /></template>
<style>
.jbr6u9bhr {
  fill: currentColor;
  d: path("M16.5 9H19a3 3 0 0 1 3 3 3 3 0 0 1 -3 3h-5a3 3 0 0 1 -3 -3 3 3 0 0 1 3 -3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q1hzqkbyz {
  fill: currentColor;
  d: path("M7.5 9H10a3 3 0 0 1 3 3 3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3 3 3 0 0 1 3 -3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.qi0s8ibkf {
  d: path("M16.5 9H19a3 3 0 0 1 3 3 3 3 0 0 1 -3 3h-5a3 3 0 0 1 -3 -3 3 3 0 0 1 3 -3Z");
}

.wn_zu_bwn {
  d: path("M7.5 9H10a3 3 0 0 1 3 3 3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3 3 3 0 0 1 3 -3Z");
}

</style>
