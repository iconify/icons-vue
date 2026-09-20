<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="k3fcinb4r"/><path class="uqqmlibsu"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ath-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.k3fcinb4r {
  fill: var(--svg-color--ea6e25, #ea6e25);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.uqqmlibsu {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.294 20h-2.127L12 6.452L10.833 20H8.706l1.93-16h2.733z");
}

</style>
