<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="l_oi1hkas"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:aioz-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.l_oi1hkas {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 20a8 8 0 1 0 0-16a8 8 0 0 0 0 16m1.51-4.225v-5.71L8.2 16.26a.75.75 0 0 1-.49.24a.68.68 0 0 1-.71-.67v-.02c0-.155.06-.31.165-.435l6.5-7.615a.77.77 0 0 1 .58-.26c.415 0 .755.33.755.735v7.54c0 .4-.335.725-.75.725a.73.73 0 0 1-.74-.725");
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
