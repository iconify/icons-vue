<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yslnx84sq"/><path class="mc92vc5nl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:link-horizontal-off-duocolor-round" /></template>
<style>
.mc92vc5nl {
  d: path("M8 8H7a4 4 0 1 0 0 8h2m6-8h2a4 4 0 0 1 3.284 6.284");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.yslnx84sq {
  stroke-opacity: 0.4;
  d: path("M8 12h4M2 2l20 20");
}

</style>
