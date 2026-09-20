<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k2mikoh9o"/><path class="k-nvl7u9w"/><path class="ai4lm938y"/><path class="eo360lbaq"/><path class="q485nsblw"/><path class="qd0z4jbov"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:dynamic-batch-outline-regular" /></template>
<style>
.ai4lm938y {
  d: path("M3.5 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.eo360lbaq {
  d: path("M8 4h2.5v16H8");
}

.k-nvl7u9w {
  d: path("M3.5 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.k2mikoh9o {
  d: path("M3.5 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q485nsblw {
  d: path("M13 12h4");
}

.qd0z4jbov {
  d: path("M16.5 9.5 19 12l-2.5 2.5");
}

</style>
