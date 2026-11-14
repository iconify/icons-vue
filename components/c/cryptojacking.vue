<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jwznjbcgn"/><path class="lm_38jblc"/><path class="s0-yawoos"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cryptojacking" /></template>
<style>
.jwznjbcgn {
  d: path("M15.2 15.5H2.5V3h19v12.5h-.7m-8.8 0V20m-4 0h7.2");
}

.lm_38jblc {
  d: path("M8 9.25a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

.s0-yawoos {
  d: path("M11 6.25h2a3 3 0 0 1 0 6h-2m7 2.25V18m0 3h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
