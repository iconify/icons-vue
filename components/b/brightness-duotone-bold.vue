<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="z705ggbcg"/><path class="dx5s6zbrc"/><path class="yazo7scbq"/><path class="jnf_2db5t"/><path class="e0ead5bmw"/><path class="f8057zb1p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:brightness-duotone-bold" /></template>
<style>
.dx5s6zbrc {
  d: path("M8 12a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

.e0ead5bmw {
  d: path("M3 12h3");
}

.f8057zb1p {
  d: path("M18 12h3");
}

.jnf_2db5t {
  d: path("M12 18v3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.yazo7scbq {
  d: path("M12 3v3");
}

.z705ggbcg {
  fill: currentColor;
  d: path("M8 12a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
