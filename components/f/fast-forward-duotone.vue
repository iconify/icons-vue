<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="m4mvh9tea"/><path class="jp41_8btc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fast-forward-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jp41_8btc {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m5.256 7.204l6 3.5a1.5 1.5 0 0 1 0 2.592l-6 3.5A1.5 1.5 0 0 1 3 15.5v-7a1.5 1.5 0 0 1 2.256-1.296m9 0l6 3.5a1.5 1.5 0 0 1 0 2.592l-6 3.5A1.5 1.5 0 0 1 12 15.5v-7a1.5 1.5 0 0 1 2.256-1.296");
}

.m4mvh9tea {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M11.256 10.704a1.5 1.5 0 0 1 0 2.592l-6 3.5A1.5 1.5 0 0 1 3 15.5v-7a1.5 1.5 0 0 1 2.256-1.296Zm9 0a1.5 1.5 0 0 1 0 2.592l-6 3.5A1.5 1.5 0 0 1 12 15.5v-7a1.5 1.5 0 0 1 2.256-1.296Z");
}

</style>
