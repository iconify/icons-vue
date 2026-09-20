<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="j3f8l8rcd"/><path class="h5ojdib5e"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:fei-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.h5ojdib5e {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.688 5.456a.8.8 0 0 0-.688-.39a.79.79 0 0 0-.688.39L9.947 7.995a.533.533 0 0 0 .458.805H13.6a.532.532 0 0 0 .459-.805L12.693 5.46zm3.163 5.467a1.07 1.07 0 0 0-.918-.523H9.067a1.07 1.07 0 0 0-.918.523l-4 6.4a1.067 1.067 0 0 0 .917 1.61h13.867a1.067 1.067 0 0 0 .918-1.61z");
}

.j3f8l8rcd {
  fill: var(--svg-color--22996f, #22996f);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
