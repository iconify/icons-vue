<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="lt7y-sk9c"/><path class="fo_mf3upf"/><path class="as_-bzbvd"/><path class="cfyvl-o0i"/><path class="mi_m6achy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:action-http-duotone-bold" /></template>
<style>
.as_-bzbvd {
  d: path("M2 9h11");
}

.cfyvl-o0i {
  d: path("M16 12h4");
}

.fo_mf3upf {
  d: path("M2 8a2 2 0 0 1 2 -2h7a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.lt7y-sk9c {
  fill: currentColor;
  d: path("M2 8a2 2 0 0 1 2 -2h7a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.mi_m6achy {
  d: path("m17 9 3 3 -3 3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
