<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xa771-t-o"/><path class="ugdbidcqi"/><path class="l0zc9ibud"/><path class="q534om6ef"/><path class="c4khiwgvb"/><path class="tldtqlb3m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:agent-config-duotone-regular" /></template>
<style>
.c4khiwgvb {
  d: path("M8 15h8");
}

.l0zc9ibud {
  d: path("M8 10h8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q534om6ef {
  d: path("M14 8v4");
}

.tldtqlb3m {
  d: path("M10 13v4");
}

.ugdbidcqi {
  d: path("M16.23 2.94a10 10 0 1 1 -8.46 0");
}

.xa771-t-o {
  fill: currentColor;
  d: path("M16.23 2.94a10 10 0 1 1 -8.46 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
