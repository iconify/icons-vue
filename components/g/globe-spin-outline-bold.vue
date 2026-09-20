<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="nrlkc9bnf"/><path class="ei_3wdi5i"/><path class="ymfnpaceh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:globe-spin-outline-bold" /></template>
<style>
.ei_3wdi5i {
  d: path("M12 20a8 8 0 0 1 0 -16");
}

.nrlkc9bnf {
  d: path("M4 12a8 8 0 1 0 16 0 8 8 0 1 0 -16 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.ymfnpaceh {
  d: path("m12 2 2.5 2.5L12 7");
}

</style>
