<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u8y0goqga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:log-tampered" /></template>
<style>
.u8y0goqga {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 2.5h16V6H3Zm0 6.25h5.5v3.5H3Zm12.15 3.5h-3.9v-3.5h9.25v2.95M3 15h11v3.5H3Zm15-.5V18m0 3h.01");
}

</style>
