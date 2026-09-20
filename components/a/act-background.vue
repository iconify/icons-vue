<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="gxgq11bfu"/><path class="y5v7-1m0k"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:act-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gxgq11bfu {
  fill: var(--svg-color--767dff, #767dff);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.y5v7-1m0k {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.216 4.5h3.568c.123 0 .245.033.351.098a.7.7 0 0 1 .257.269l5.52 10.266a.75.75 0 0 1 0 .708l-1.76 3.292a.7.7 0 0 1-.257.27a.7.7 0 0 1-.352.097H6.457a.7.7 0 0 1-.352-.098a.7.7 0 0 1-.256-.269l-1.76-3.292a.75.75 0 0 1 0-.707L9.6 4.867a.7.7 0 0 1 .257-.269a.7.7 0 0 1 .351-.098zM12 8.584L8.28 15.5h7.44z");
}

</style>
