<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGEwRXn23v)" class="r4i437pya"/><path class="odd2css2i"/></g><defs><linearGradient id="SVGEwRXn23v" x1="12" x2="12" y1="4.8" y2="19.2" gradientUnits="userSpaceOnUse"><stop class="yxjozoyqt"/><stop offset="1" class="kmm55pb3i"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:apex-layer-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.kmm55pb3i {
  stop-color: var(--svg-color--00cffc, #00cffc);
}

.odd2css2i {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.825 7.47c-.289.17-.62.234-.948.201q-.3-.031-.645-.032C5.55 7.639 4.69 8.23 4 8.897v3.418c.774-.727 1.43-1.46 3.232-1.46v.017l.158-.014c1.36.033 2.04.504 2.647 1.055c-.37.384-.721.763-1.173 1.039a1.52 1.52 0 0 1-.97.21a6 6 0 0 0-.662-.034c-1.682 0-2.543.593-3.232 1.259v3.417c.774-.726 1.43-1.459 3.232-1.459v.03q.13-.01.255-.024c3.093.127 2.57 2.578 6.13 2.849v-2.996c-1.499 0-2.136-.777-2.886-1.551c.651-.604 1.355-1.132 2.885-1.132c3.38 0 2.728 2.577 6.384 2.854v-2.996c-2.979 0-2.554-3.074-6.384-3.074c-.297 0-.52.008-.73.032a1.53 1.53 0 0 1-1.01-.224a6.5 6.5 0 0 1-1.152-.959c.653-.606 1.356-1.139 2.892-1.139c3.38 0 2.728 2.578 6.384 2.854V7.874c-2.98 0-2.554-3.074-6.384-3.074c-2.96 0-3.378 1.836-4.79 2.67z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.yxjozoyqt {
  stop-color: var(--svg-color--004ef4, #004ef4);
}

</style>
