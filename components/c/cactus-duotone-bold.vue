<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="m3715abai"/><path class="q3dgvqbzs"/><path class="wcoay0fmb"/><path class="ri0jcjret"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cactus-duotone-bold" /></template>
<style>
.m3715abai {
  fill: currentColor;
  d: path("M9 21V5h6v16Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.q3dgvqbzs {
  d: path("M9 21V5h6v16Z");
}

.ri0jcjret {
  d: path("M15 15h4v-5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wcoay0fmb {
  d: path("M9 12H5V8");
}

</style>
