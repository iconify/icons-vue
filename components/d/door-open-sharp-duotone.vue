<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="fzq72nb8g"/><path class="cu3-8sblw"/><path class="g3oaxt9cr"/><path clip-rule="evenodd" class="dgzq6fb_u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:door-open-sharp-duotone" /></template>
<style>
.cu3-8sblw {
  d: path("M1 21L10.5517 21M14 21L23 21");
}

.dgzq6fb_u {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.7575 3.0299L13.7575 1.0299C13.8368 1.01 13.9182 1 14 1C14.5523 1 15 1.4477 15 2L15 22C15 22.5523 14.5523 23 14 23C13.9058 23 13.812 22.9867 13.7215 22.9604L5.7215 20.6404C5.2941 20.5165 5 20.125 5 19.68L5 4C5 3.5411 5.3123 3.1411 5.7575 3.0299ZM12 10L10 10L10 14L12 14L12 10Z");
  stroke: none;
}

.fzq72nb8g {
  stroke-opacity: 0.4;
  d: path("M18 21L18 3L14 3");
}

.g3oaxt9cr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 10L10 10L10 14L12 14L12 10Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
