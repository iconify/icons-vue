<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bs2e4pbkx"/><path class="hm5lrwnqe"/><path class="u3l92vzhy"/><path class="hmsnaubya"/><path class="jot0llbot"/><path class="r_86v5bdw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:evacuation-duotone-regular" /></template>
<style>
.bs2e4pbkx {
  fill: currentColor;
  d: path("M4 6a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hm5lrwnqe {
  d: path("M13 3h8v18h-8");
}

.hmsnaubya {
  d: path("M7 9v5l-3 3");
}

.jot0llbot {
  d: path("m7 14 3 3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r_86v5bdw {
  d: path("M4 11h6");
}

.u3l92vzhy {
  d: path("M4 6a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
