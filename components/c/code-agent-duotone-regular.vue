<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hwckqco0e"/><path class="xzchytbqj"/><path class="bn01d2bwj"/><path class="pl_bf8bxp"/><path class="rdh7npbwk"/><path class="cr7psearj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:code-agent-duotone-regular" /></template>
<style>
.bn01d2bwj {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m15 13 2.5 2.5L15 18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.cr7psearj {
  d: path("m15 13 2.5 2.5L15 18");
}

.hwckqco0e {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13.69 2.87a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pl_bf8bxp {
  d: path("M13.69 2.87a4 4 0 1 1 -3.38 0");
}

.rdh7npbwk {
  d: path("m9 13 -2.5 2.5L9 18");
}

.xzchytbqj {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m9 13 -2.5 2.5L9 18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
