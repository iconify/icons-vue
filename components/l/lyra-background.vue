<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGVPn6gdxm)" class="r4i437pya"/><path class="peo9lwxew"/></g><defs><linearGradient id="SVGVPn6gdxm" x1="12" x2="12" y1="3.995" y2="20" gradientUnits="userSpaceOnUse"><stop class="vnu3zelit"/><stop offset="1" class="j4oi4gbng"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lyra-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.j4oi4gbng {
  stop-color: var(--svg-color--37c4b1, #37c4b1);
}

.peo9lwxew {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.453 10.203L12.667 13H5.61c-.51 0-.766-.585-.42-.935l7.886-7.937a.44.44 0 0 1 .705.12l1.966 4.376a1.41 1.41 0 0 1-.295 1.58M4 13.499c.16.215.735.5 1.73.5h10.953c.635 0 1.21.37 1.46.95l1.815 4.29a.55.55 0 0 1-.51.76H8.021a1.8 1.8 0 0 1-1.65-1.07z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.vnu3zelit {
  stop-color: var(--svg-color--5adcd3, #5adcd3);
}

</style>
