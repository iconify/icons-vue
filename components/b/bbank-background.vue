<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="hgyd7zboc"/><path class="ceb-pybbx"/><path class="ll6qpab3k"/><path class="tbbce5brw"/><path clip-rule="evenodd" class="sfext73et"/><path class="egx35wb4l"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:bbank-background" /></template>
<style>
.ceb-pybbx {
  fill: var(--svg-color--fff, #fff);
  d: path("M5.698 4h1.454v9.695H5.698z");
}

.egx35wb4l {
  fill: var(--svg-color--fff, #fff);
  d: path("m9.091 10.545l1.455-.728v1.842a2.894 2.894 0 0 1 3.815.824c-.931 0-2.245-.048-3.088.437c-1.435.829-1.63 2.966-1.63 2.966a2.9 2.9 0 0 1-.552-1.706z");
}

.ft5dv1b6b {
  fill: none;
}

.hgyd7zboc {
  fill: var(--svg-color--f26122, #f26122);
  d: path("M24 0H0v24h24z");
}

.ll6qpab3k {
  fill: var(--svg-color--fff, #fff);
  d: path("M5.698 4h1.454v3.393S6.91 5.212 5.698 4m12.604 9.695a6.302 6.302 0 1 1-11.15-4.023v4.023a4.847 4.847 0 1 0 1.455-3.461V8.382a6.302 6.302 0 0 1 9.695 5.313");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.sfext73et {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("m10.546 9.817l-1.454.727v3.636a2.909 2.909 0 1 0 1.454-2.52zm0 4.363a1.455 1.455 0 1 0 2.91 0a1.455 1.455 0 0 0-2.91 0");
}

.tbbce5brw {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.3 13.695c0-4.1-4.968-5.943-8.317-4.411c-.511.236-.977.56-1.377.955V8.387a6.302 6.302 0 0 1 9.695 5.308");
}

</style>
