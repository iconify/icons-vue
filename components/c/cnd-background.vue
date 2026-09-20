<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path clip-rule="evenodd" class="x6t1a5bqg"/><path class="au0zzyb0m"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:cnd-background" /></template>
<style>
.au0zzyb0m {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 13a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

.ft5dv1b6b {
  fill: none;
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.x6t1a5bqg {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 19a7 7 0 1 0 0-14a7 7 0 0 0 0 14m0 1a8 8 0 1 0 0-16a8 8 0 0 0-8 8a8 8 0 0 0 8 8");
}

</style>
