<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="snmd_fbii"/><path class="deqyo3b1u"/><path class="by45ng8be"/><path class="pv0pzub8j"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:bat-background" /></template>
<style>
.by45ng8be {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.95 18.386L12.317 5.25A.37.37 0 0 0 12 5.067v5.332l3.284 5.878l4.666 2.478a.37.37 0 0 0 0-.37");
}

.deqyo3b1u {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 5.067a.37.37 0 0 0-.318.184L4.05 18.386a.37.37 0 0 0 0 .368l4.658-2.488l3.294-5.868z");
}

.ft5dv1b6b {
  fill: none;
}

.pv0pzub8j {
  fill: var(--svg-color--fff, #fff);
  d: path("m19.95 18.763l-4.662-2.496H8.711l-4.663 2.496a.36.36 0 0 0 .135.125q.087.045.184.045H19.63a.4.4 0 0 0 .185-.045a.36.36 0 0 0 .136-.125");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.snmd_fbii {
  fill: var(--svg-color--ff4724, #ff4724);
  d: path("M24 0H0v24h24z");
}

</style>
