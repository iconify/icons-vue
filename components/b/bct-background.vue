<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="rux0rvbxg"/><path class="d42j39byu"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:bct-background" /></template>
<style>
.d42j39byu {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.683 4.13a.455.455 0 0 1 .636 0l3.212 3.212a.456.456 0 0 1 0 .645l-3.207 3.207a.46.46 0 0 1-.498.1a.5.5 0 0 1-.148-.1L8.471 7.988a.455.455 0 0 1 0-.645zm4.329 4.34a.454.454 0 0 1 .646 0l3.207 3.207a.46.46 0 0 1 .1.498a.5.5 0 0 1-.1.148l-3.207 3.207a.456.456 0 0 1-.646 0l-3.207-3.207a.455.455 0 0 1 0-.646zm-4.33 4.336a.456.456 0 0 1 .636 0l3.212 3.207a.457.457 0 0 1 0 .645l-3.207 3.207a.454.454 0 0 1-.646 0L8.47 16.66a.455.455 0 0 1 0-.646l3.207-3.208zM7.342 8.47a.455.455 0 0 1 .646 0l3.207 3.207a.46.46 0 0 1 .134.323a.46.46 0 0 1-.134.323L7.988 15.53a.456.456 0 0 1-.646 0l-3.207-3.207a.453.453 0 0 1 0-.646z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.rux0rvbxg {
  fill: var(--svg-color--00a0e1, #00a0e1);
  d: path("M24 0H0v24h24z");
}

</style>
