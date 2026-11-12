<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="n6tc07bpg"/><path class="jwvedsvir"/><path class="sqy-cgo_l"/><path class="g6m793csp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bonfire-linear" /></template>
<style>
.g6m793csp {
  d: path("M15 10C14.8 10.6667 13.92 12 12 12");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jwvedsvir {
  d: path("M20 15L4 22");
}

.n6tc07bpg {
  d: path("M11.6 15C13.7333 15 18 13.7615 18 8.80745C18 5.776 16.1512 3.5774 14.4009 2.2646C13.503 1.59108 12.3529 2.28965 12.3529 3.38896C12.3529 4.13169 12.1424 5.36614 11.5596 6.27998C10.8777 7.34944 9.75127 6.421 9.57296 5.17624C9.48354 4.55201 8.79638 4.29388 8.26099 4.65274C7.20839 5.35826 6 6.71017 6 8.80745C6 13.7615 9.73333 15 11.6 15Z");
}

.sqy-cgo_l {
  d: path("M4 15L9 17.1875M14.5 19.5938L20 22");
}

</style>
