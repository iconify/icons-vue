<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGMISvxcYN)" class="r4i437pya"/><path class="gfvvxrbca"/></g><defs><linearGradient id="SVGMISvxcYN" x1="15.817" x2="7.282" y1="4.883" y2="18.804" gradientUnits="userSpaceOnUse"><stop class="t8o9bgbpc"/><stop offset=".39" class="bwyzp35jz"/><stop offset=".57" class="cb_2bmn7s"/><stop offset="1" class="nllcsxbel"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:isk-background" /></template>
<style>
.bwyzp35jz {
  stop-color: var(--svg-color--6691da, #6691da);
}

.cb_2bmn7s {
  stop-color: var(--svg-color--2baaea, #2baaea);
}

.ft5dv1b6b {
  fill: none;
}

.gfvvxrbca {
  fill: var(--svg-color--fff, #fff);
  d: path("m11.908 4l5.945 5.827a2.934 2.934 0 0 1 0 4.21l-1.832 1.795l-4.11-4.03a5.443 5.443 0 0 1 0-7.802zm.185 16l-5.946-5.827a2.934 2.934 0 0 1 0-4.21L7.98 8.167l4.11 4.03a5.45 5.45 0 0 1 1.218 6.018A5.45 5.45 0 0 1 12.088 20z");
}

.nllcsxbel {
  stop-color: var(--svg-color--003a9f, #003a9f);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.t8o9bgbpc {
  stop-color: var(--svg-color--fa2a9b, #fa2a9b);
}

</style>
