<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n9iuwztor"/><path class="yojl-bcym"/><path class="ln45oobno"/><path class="ju9h4zuus"/><path class="x2cdhib-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:artboard-outline-regular" /></template>
<style>
.ju9h4zuus {
  d: path("M3 18v3h3");
}

.ln45oobno {
  d: path("M18 3h3v3");
}

.n9iuwztor {
  d: path("M7 9a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H9a2 2 0 0 1 -2 -2Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.x2cdhib-a {
  d: path("M18 21h3v-3");
}

.yojl-bcym {
  d: path("M3 6V3h3");
}

</style>
