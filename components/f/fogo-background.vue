<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="unapy8b0i"/><path clip-rule="evenodd" class="q3lq9m6fd"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:fogo-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q3lq9m6fd {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 20a8 8 0 1 0 0-16a8 8 0 0 0 0 16m2.653-12.733h-3.298l-.473 1.895H9.459l-.598 2.403a.507.507 0 0 0 .488.628h1.205l-1.13 4.54l3.843-4.066a.506.506 0 0 0-.365-.853h-1.838l.566-2.274h3.102l.41-1.645a.51.51 0 0 0-.092-.433a.51.51 0 0 0-.396-.195");
}

.unapy8b0i {
  fill: var(--svg-color--ff3d00, #ff3d00);
  d: path("M24 0H0v24h24z");
}

</style>
